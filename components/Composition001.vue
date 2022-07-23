<template>
  <div class="grid-wrapper">
    <div class="alpha-1">A</div>
    <div class="alpha-2">L</div>
    <div class="alpha-3">P</div>
    <div class="alpha-4">H</div>
    <div class="alpha-5">A</div>
    <div class="alpha-6">N</div>
    <div class="alpha-7">U</div>
    <div class="alpha-8">M</div>
    <div class="alpha-9">E</div>
    <div class="alpha-10">RRRRRRRRRRRRRRR</div>
    <div class="alpha-11">I</div>
    <div class="alpha-12">C</div>
  </div>
</template>

<style scoped>
  .grid-wrapper {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: 4;
    height: 100%;
    min-height: 20 rem;
  }

  .grid-wrapper > div {
    padding: 10rem 0;
    font-family: "Decimal A", "Decimal B";
    font-style: normal;
    font-weight: 400;
  }

  .alpha-1 {grid-column: 3; grid-row: 1}
  .alpha-2 {grid-column: 4; grid-row: 1}
  .alpha-3 {grid-column: 4; grid-row: 2}
  .alpha-4 {grid-column: 5; grid-row: 2}
  .alpha-5 {grid-column: 6; grid-row: 2}
  .alpha-6 {grid-column: 7; grid-row: 2}
  .alpha-7 {grid-column: 7; grid-row: 3}
  .alpha-8 {grid-column: 8; grid-row: 3}
  .alpha-9 {grid-column: 8; grid-row: 4}
  .alpha-10 {grid-column: 9; grid-row: 4}
  .alpha-11 {grid-column: 10; grid-row: 4}
  .alpha-12 {grid-column: 11; grid-row: 4}

</style>