<template>
<div class="row">
  <div class="col-2">...</div>

  <!-- 2 + 6 < 12, so next element is placed on same line -->
  <div class="col-6">...</div>

  <!-- 2 + 6 + 10 > 12, so next element wraps to next line -->
  <div class="col-10">...</div>

  <!--
    10 + 3 > 12, so next element wraps to next line.
    Note that we take into consideration the current line only
    (with col-10 only, since it was wrapped to its own line).
  -->
  <div class="col-3">...</div>
</div>
</template>
