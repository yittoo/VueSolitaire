<template>
  <div class="card holder" style="cursor:pointer;" draggable="true"></div>
</template>
<script>
export default {
  name: "Holder",
  data: function() {
    return {
      isDisplayed: false
    };
  }
};
</script>

<style>
.holder {
  opacity: 0;
}
.display {
  display: block;
}
.notDisplay {
  display: none;
}
.card_stack {
  position: relative;
  margin-bottom: -100px;
}
.card {
  box-shadow: 0px -1px 10px rgba(0, 0, 0, 0.5);
  width: 7vw;
  height: 140px;
  border-radius: 4px;
  border: 1px solid black;
  padding: 0;
}
</style>