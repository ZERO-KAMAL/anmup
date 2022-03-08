<template>
  <div class="container section__padding">
    <div class="row">
      <div class="col-md-6 d-flex flex-column">
        <label for="customRange3" class="form-label">Example range</label>
        <input type="range" min="500" max="5000" step="500" v-model="value_1" />
        <output>{{ value_1 }}</output>
      </div>
      <div class="col-md-6 d-flex flex-column">
        <label for="customRange3" class="form-label">Example range</label>
        <input
          type="range"
          min="1000"
          max="10000"
          step="1000"
          v-model="value_2"
        />
        <output>{{ value_2 }}</output>
      </div>

      <div class="col-md-4">
        <table>
          <thead>
            <th>value_1</th>
            <th>Value_2</th>
          </thead>
          <tbody>
            <tr>
              <td>{{ value_1 }}</td>
              <td>{{ value_2 }}</td>
            </tr>
            <tr>
              <td style="font-weight: bold; text-transform: uppercase">
                total
              </td>
              <td colspan="1" style="color: red; font-weight: bold">
                {{ total }}
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RangeValue",
  data() {
    return {
      value_1: "500",
      value_2: "1000",
    };
  },
  computed: {
    total() {
      return parseInt(this.value_1) + parseInt(this.value_2);
    },
  },
};
</script>


