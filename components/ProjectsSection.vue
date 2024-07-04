<template>
    <section id="works" class="menu">
            <h2>My<span> Works</span></h2>
            <div class="row">
                <div class="menu-card">
                    <img src="assets/Neckdeep 1.png" 
                    alt="yal-img" class="menu-card-image">
                    <h3 class="menu-card-title">
                        Neckdeep 1
                    </h3>
                </div>
                <div class="menu-card">
                    <img src="assets/Neckdeep 2.png"
                        alt="yal-img" class="menu-card-image">
                    <h3 class="menu-card-title">
                        Neckdeep 2
                    </h3>
                </div>
                <div class="menu-card">
                    <img src="assets/Neckdeep 3.png"
                        alt="yal-img" class="menu-card-image">
                    <h3 class="menu-card-title">
                        Neckdeep 3
                    </h3>
                </div>
            </div>
            <div class="row">
                <div class="menu-card">
                    <img src="assets/Viva.png" 
                    alt="yal-img" class="menu-card-image">
                    <h3 class="menu-card-title">
                        Viva La Vida
                    </h3>
                </div>
                <div class="menu-card">
                    <img src="assets/Yellow.png"
                        alt="yal-img" class="menu-card-image">
                    <h3 class="menu-card-title">
                        Yellow
                    </h3>
                </div>
                <div class="menu-card">
                    <img src="assets/Stars.png"
                        alt="yal-img" class="menu-card-image">
                    <h3 class="menu-card-title">
                        A Sky Full Of Stars
                    </h3>
                </div>
            </div>
        </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: #e9ecef;
  text-align: center;
}

h2 {
  font-size: 2em;
  margin-bottom: 20px;
}

h2 span {
  color: #007bff;
}

.row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin: 0 -15px;
}

.menu-card {
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 5px;
  margin: 15px;
  width: 200px;
  padding: 15px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.menu-card:hover {
  transform: translateY(-10px);
}

.menu-card-image {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.menu-card-title {
  font-size: 1.25em;
  margin-top: 15px;
}
</style>

