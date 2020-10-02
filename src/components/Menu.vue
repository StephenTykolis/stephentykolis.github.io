<template>
  <div id="menu">
    <!--<p @click="showMenu">menu</p>
		<transition name="expand">
			<span class="dot"></span>
    </transition>-->
    <p>Coming soon!</p>
  </div>
</template>

<script>
export default {
  name: "Menu",
};
</script>

<style>
.expand-enter {
  transition: scale(0, 0);
}

.expand-enter-active {
  transition: scale(5, 5) linear;
}
</style>

<style scoped>
p {
  text-align: center;
  border-radius: 100%;
  display: inline-flex;
  flex-direction: column;
  justify-content: center;
  color: white;
  text-decoration: none;
  font-size: 1.5rem;
  z-index: 2;
  position: relative;
  right: -35px;
  top: -30px;
}

div {
  position: absolute;
  top: 85%;
  text-align: center;
  margin: auto;
  width: 100%;
}
.dot {
  height: 7rem;
  width: 7rem;
  background-color: #f34213;
  border-radius: 50%;
  display: inline-block;
  position: relative;
  z-index: 1;
  left: -20px;
  cursor: pointer;
}
</style>
