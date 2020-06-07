<template>
  <div id="app" class="m-4">
    <div class="container">
      <div class="bg-light p-2 rounded shadow-sm border">
        <h5 class="text-muted">Colors</h5>
        <div class="row">
          <div class="col-6">
            <div class="card p-2 m-2">
              <div class="row">
                <div class="col-6 bg-aqua-light">
                  <div class="card-body">aqua-light</div>
                </div>
                <div class="col-6 bg-aqua">
                  <div class="card-body">aqua</div>
                </div>
              </div>
              <div class="row">
                <div class="col-6 bg-aqua-lighter">
                  <div class="card-body">aqua-lighter</div>
                </div>
                <div class="col-6 bg-aqua-muted">
                  <div class="card-body">aqua-muted</div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6">
            <div class="card p-2 m-2">
              <div class="row">
                <div class="col-6 bg-purple-light">
                  <div class="card-body">purple-light</div>
                </div>
                <div class="col-6 bg-purple-lighter">
                  <div class="card-body">purple-lighter</div>
                </div>
              </div>
              <div class="row">
                <div class="col-6 bg-purple">
                  <div class="card-body">purple</div>
                </div>
                <div class="col-6 bg-purple-muted">
                  <div class="card-body">purple-muted</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-6">
            <div class="card p-2 m-2">
              <div class="row">
                <div class="col-6 bg-green">green</div>
                <div class="col-6">
                  <div class="row">
                    <div class="col-12 bg-green-muted">green-muted</div>
                  </div>
                  <div class="row">
                    <div class="col-12 bg-green-dark">green-dark</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6">
            <div class="card p-2 m-2">
              <div class="row">
                <div class="col-6 bg-red">red</div>
                <div class="col-6">
                  <div class="row">
                    <div class="col-12 bg-red-muted">red-muted</div>
                  </div>
                  <div class="row">
                    <div class="col-12 bg-red-dark">red-dark</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-6">
            <div class="card p-2 m-2">
              <div class="row">
                <div class="col-6 bg-black">black</div>
                <div class="col-6">
                  <div class="row">
                    <div class="col-12 bg-black-muted">black-muted</div>
                  </div>
                  <div class="row">
                    <div class="col-12 bg-black-dark">black-dark</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6">
            <div class="card w-100">
              <div class="row">
                <div class="col-6">
                  <div class="card w-100 p-2 m-2 bg-muted">muted</div>
                </div>
                <div class="col-6">
                  <div class="card w-100 p-2 m-2 bg-dark">dark</div>
                </div>
              </div>
              <div class="row">
                <div class="col-6">
                  <div class="card w-100 p-2 m-2 bg-grey">grey</div>
                </div>
                <div class="col-6">
                  <div class="card w-100 p-2 m-2 bg-white">white</div>
                </div>
              </div>
              <div class="row">
                <div class="col-12">
                  <div class="card w-100 p-2 m-2 bg-light">light</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style lang="scss">
$aqua-lighter: rgb(166, 233, 223);
$aqua-light: rgb(139, 227, 223);
$aqua: rgb(119, 214, 211);
$aqua-muted: rgb(111, 199, 194);

$purple-lighter: rgb(225, 165, 190);
$purple-light: rgb(187, 131, 169);
$purple: rgb(175, 118, 155);
$purple-muted: rgb(138, 81, 116);

$green: rgb(146, 191, 112);
$green-muted: rgb(137, 188, 102);
$green-dark: rgb(127, 168, 98);

$red: rgb(236, 92, 92);
$red-muted: rgb(215, 75, 75);
$red-dark: rgb(188, 55, 55);

$black: #0d1b22;
$black-muted: #12222b;
$black-dark: #0a151b;

$dark: #494c4e;
$muted: #576369;
$grey: #adb6ba;
$light: #eeeff2;
$white: #fcfcfd;

$sans: Lato, sans-serif;
$serif: Lora, serif;

/*BACKGROUND STUFF*/
bg-aqua {
  background-color: $aqua;
}

bg-aqua-light {
  background-color: $aqua-light;
}

bg-aqua-lighter {
  background-color: $aqua-lighter;
}

bg-aqua-muted {
  background-color: $aqua-muted;
}

bg-purple {
  background-color: $purple;
}

bg-purple-light {
  background-color: $purple-light;
}

bg-purple-lighter {
  background-color: $purple-lighter;
}

bg-purple-muted {
  background-color: $purple-muted;
}

bg-green {
  background-color: $green;
}

bg-green-muted {
  background-color: $green-muted;
}

bg-green-dark {
  background-color: $green-dark;
}

bg-red {
  background-color: $red;
}

bg-red-muted {
  background-color: $red-muted;
}

bg-red-dark {
  background-color: $red-dark;
}

bg-dark {
  background-color: $dark;
}
bg-muted {
  background-color: $muted;
}
bg-grey {
  background-color: $grey;
}
bg-white {
  background-color: $white;
}

/*TEXT STUFF*/
text-red {
  color: $red;
}

text-aqua {
  color: $aqua;
}

text-green {
  color: $green;
}

text-purple {
  color: $purple;
}

#app {
  font-family: $sans;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: $black-muted;
}
</style>
