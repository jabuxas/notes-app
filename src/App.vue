<template>
  <main>
    <div class="overlay">
      <div class="modal">
        <textarea name="note" id="note" rows="15" cols="30"></textarea>
        <button>Add Note</button>
        <button class="close">Close</button>
      </div>
    </div>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
      <div class="cards-container">
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis veritatis impedit magni nam, harum sunt non
            animi quos. Neque ipsam a velit quod porro cum saepe hic veritatis facilis ut?
          </p>
          <p class="date">04/10/2021</p>
        </div>
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis veritatis impedit magni nam, harum sunt non
            animi quos. Neque ipsam a velit quod porro cum saepe hic veritatis facilis ut?
          </p>
          <p class="date">04/10/2021</p>
        </div>
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis veritatis impedit magni nam, harum sunt non
            animi quos. Neque ipsam a velit quod porro cum saepe hic veritatis facilis ut?
          </p>
          <p class="date">04/10/2021</p>
        </div>
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis veritatis impedit magni nam, harum sunt non
            animi quos. Neque ipsam a velit quod porro cum saepe hic veritatis facilis ut?
          </p>
          <p class="date">04/10/2021</p>
        </div>
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis veritatis impedit magni nam, harum sunt non
            animi quos. Neque ipsam a velit quod porro cum saepe hic veritatis facilis ut?
          </p>
          <p class="date">04/10/2021</p>
        </div>
      </div>
    </div class="container">
  </main>
</template>

<style scoped>
main {
  height: 100vh;
  width: 100vw;
}

.container {
  max-width: 1000px;
  padding: 10px;
  margin: 0 auto;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h1 {
  font-weight: bold;
  margin-bottom: 25px;
  font-size: 75px;
}

header button {
  border: none;
  padding: 10px;
  width: 50px;
  height: 50px;
  cursor: pointer;
  background-color: rgb(21, 20, 20);
  border-radius: 100%;
  color: white;
  font-size: 20px;
}

.card {
  width: 225px;
  height: 225px;
  background-color: rgb(237, 182, 44);
  padding: 10px;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin: 0 20px 20px 0;
}

.date {
  font-size: 12.5px;
  font-weight: bold;
}

.cards-container {
  display: flex;
  flex-wrap: wrap;
}

.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: rgb(0, 0, 0, 0.77);
  z-index: 10;
  display: flex;
  align-items: center;
  justify-content: center;
}

.modal {
  width: 750px;
  background-color: white;
  border: 10px;
  padding: 30px;
  position: relative;
  display: flex;
  flex-direction: column;
}

.modal button {
  padding: 10px 20px;
  font-size: 20px;
  width: 100%;
  background-color: blueviolet;
  border: none;
  color: white;
  cursor: pointer;
  margin-top: 15px;
}

.modal .close {
  background-color: red;
  margin-top: 7px;
}
</style>
