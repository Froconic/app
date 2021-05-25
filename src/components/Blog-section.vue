<template>
  <b-container id="blog-section" class="section blog-section">
    <b-row class="mb-5" align-h=center>
      <b-col>
        <h2>Blog</h2>
      </b-col>
    </b-row>
    <b-row class=mb-5>
      <b-col>
        <h3 class="mb-5">Featured</h3>
        <b-row>
          <b-col>
            <b-card header-tag="h2" header="Title" title="Category" overlay img-src="https://picsum.photos/900/250/?image=3">
              <b-card-text>
                Ut id sit veniam incididunt cillum eu cillum sunt.
                <h6 class="card-date">Date</h6>
                <b-button variant=outline>
                  <b-icon-box-arrow-in-right class="card-btn"></b-icon-box-arrow-in-right>
                </b-button>
              </b-card-text>
            </b-card>
          </b-col>
        </b-row>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <b-card header-tag="h2" header="Boop" title="Category" img-top img-src="https://picsum.photos/900/250/?image=3">
          <b-card-text>
            Ut id sit veniam incididunt cillum eu cillum sunt.
            <h6 class="card-date">Date</h6>
            <b-button variant=outline>
              <b-icon-box-arrow-in-right class="card-btn"></b-icon-box-arrow-in-right>
            </b-button>
          </b-card-text>
        </b-card>
      </b-col>
      <b-col>
        <b-card title=Title sub-title=Category>
          <h6>Date</h6>
          <b-button variant=outline>
            <b-icon-box-arrow-in-right></b-icon-box-arrow-in-right>
          </b-button>
        </b-card>
      </b-col>
      <b-col>
        <b-card title=Title sub-title=Category>
          <h6>Date</h6>
          <b-button variant=outline>
            <b-icon-box-arrow-in-right></b-icon-box-arrow-in-right>
          </b-button>
        </b-card>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <b-icon icon=arrow-down font-scale=5></b-icon>
      </b-col>
    </b-row>
  </b-container>
</template>
<script>
  export default {}
</script>
<style>
  .card {
    background: rgba(0, 0, 0, 0.15);
    -webkit-box-shadow: 0px 0px 25px 8px rgba(0, 0, 0, 0.75);
    -moz-box-shadow: 0px 0px 25px 8px rgba(0, 0, 0, 0.75);
    box-shadow: 0px 0px 25px 8px rgba(0, 0, 0, 0.75);
    backdrop-filter: blur(12.5px);
    -webkit-backdrop-filter: blur(12.5px);
    border-radius: 10px;
    height: 100%;
  }

  .card-body {
    background: rgba(0, 0, 0, 1);
    background: -moz-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: -webkit-gradient(left top, left bottom, color-stop(0%, rgba(0, 0, 0, 1)), color-stop(0%, rgba(112, 112, 112, 1)), color-stop(7%, rgba(0, 0, 0, 0.96)), color-stop(100%, rgba(255, 255, 255, 0.42)));
    background: -webkit-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: -o-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: -ms-linear-gradient(top, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    background: linear-gradient(to bottom, rgba(0, 0, 0, 1) 0%, rgba(112, 112, 112, 1) 0%, rgba(0, 0, 0, 0.96) 7%, rgba(255, 255, 255, 0.42) 100%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#000000', endColorstr='#ffffff', GradientType=0);
  }

  .card-title {
    color: #EBF4FF;
  }

  .card-subtitle {
    color: #001429;
  }

  .card-text {
    color: #F4F5F6;
  }

  .card-date {
    color: #F4F5F6;
  }

  .card-btn {
    color: #F4F5F6;
  }
</style>