<style>
    @import '../Dashboard/dashboard.css';
    @import '../../css/config.css';
</style>


<template>
  <div class="hello">
    <!--Navbar-->
    <div class="sidebar">
        <div class="img-prof">
            <img src="../../assets/ei.jpg">
            <h3>Enrique Iglesias</h3>
            <h1>$387,098</h1>
        </div>
        <a href="#apps">APPLICATIONS</a>
        <a href="#analysis"><i class="fas fa-chart-bar icon"></i> Analytics</a>
        <a href="#problem"><i class="far fa-comment-alt icon"></i>Problem</a>
        <a href="#search"><i class="fas fa-search icon"></i>Search</a>
        
        <a href="#modules" id="mods">MODULES</a>
        <ul class="mods">
        <li><a href="#">Finance</a></li>
        <li><a href="#">Orders</a></li>
        <li><a href="#">Delivery</a></li>
        <li><a href="#">Resource</a></li>
        <li><a href="#">Support</a></li>
        </ul>
    </div>


    <!--Main Section-->
    <div class="main">
      <div class="container-fluid">
      <h3>Dashboard</h3>
      <!---Top Card Section--->
      <div class="back-card">
        <div class="row">

          <div class="col-md-3">
            <div class="card">
              <i class="fas fa-globe fa-2x">&nbsp;&nbsp;<span id="icon-head">Page Visits</span></i>
              <h3>22,490</h3>
              <h6 id="top-cardtext">6% From Last Week</h6>
            </div>
          </div>

          <div class="col-md-3">
            <div class="card">
              <i class="far fa-user fa-2x">&nbsp;&nbsp;<span id="icon-head">Total Earning</span></i>
              <h3>$45,231</h3>
              <h6 id="top-cardtext">6% From Last Week</h6>
            </div>
          </div>

          <div class="col-md-3">
            <div class="card">
              <i class="fas fa-cart-plus fa-2x">&nbsp;&nbsp;<span id="icon-head">Impression</span></i>
              <h3>$82,490</h3>
              <h6 id="top-cardtext">6% From Last Week</h6>
            </div>
          </div>

          <div class="col-md-3">
            <div class="card">
              <i class="far fa-clipboard fa-2x">&nbsp;&nbsp;<span id="icon-head">Site Income</span></i>
              <h3>$34,542</h3>
              <h6 id="top-cardtext">6% From Last Week</h6>
            </div>
          </div>

        </div>
      </div>

      <!---Second Card Section--->

      <div class="row">
      
        <div class="col-md-6 ">
          <div class="back-card">
          <h3 id="icon-head">Acquisition</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid quaerat ad quibusdam vero iure cupiditate saepe similique odit maiores.
          </p>
          <div class="row">
            
            <div class="col-md-4">
              <div class="row">
                <div class="col-md-2">
                  <i class="fas fa-chart-bar br-chart fa-2x"></i>
                </div>
                <div class="col-md-10 acqtxt">
                  <h6 id="top-cardtext">Bounce Rate</h6>
                  <h3>26.80%</h3>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="row">
                <div class="col-md-2">
                  <i class="fas fa-chart-bar s-chart fa-2x"></i>
                </div>
                <div class="col-md-10 acqtxt">
                  <h6 id="top-cardtext">Sessions</h6>
                  <h3>9,065</h3>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="row">
                <div class="col-md-2">
                  <i class="fas fa-chart-bar pv-chart fa-2x"></i>
                </div>
                <div class="col-md-10 acqtxt">
                  <h6 id="top-cardtext">Page Views</h6>
                  <h3>83,123</h3>
                </div>
              </div>
            </div>

          </div>
          </div>
        </div>
      
        <div class="col-md-6 ">
          <div class="back-card">
          <h3 id="icon-head">Fleat activity map</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid quaerat ad quibusdam vero iure cupiditate saepe similique odit maiores.
          </p>
          <div class="row">
            
            <div class="col-md-4">
              <div class="row">
                <div class="col-md-2">
                  <!-- <i class="fas fa-chart-bar br-chart fa-2x"></i> -->
                  <!-- <canvas id="sessions"></canvas> -->
                  <chartjs-doughnut :width="100" :height="100" v-bind:datasets="datasets"></chartjs-doughnut>
                </div>
                <div class="col-md-10 acqtxt">
                  <h6 id="top-cardtext">% New Sessions</h6>
                  <h3>26.80%</h3>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="row">
                <div class="col-md-2">
                  <i class="fas fa-chart-bar s-chart fa-2x"></i>
                </div>
                <div class="col-md-10 acqtxt">
                  <h6 id="top-cardtext">Pages</h6>
                  <h3>9,065</h3>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="row">
                <div class="col-md-2">
                  <i class="fas fa-chart-bar pv-chart fa-2x"></i>
                </div>
                <div class="col-md-10 acqtxt">
                  <h6 id="top-cardtext">Users</h6>
                  <h3>83,123</h3>
                </div>
              </div>
            </div>

          </div>
          </div>
        </div>
      </div>



      <!--------------Third Cards Section-------------------->
      <div class="row">

        <div class="col-md-8">
          <div class="back-card">
            <div class="row">
              <div class="col-md-8">
                <h6>Realtime Statistics<span class="badge new">New</span></h6>
                <h1>24.436%</h1>
              </div>
              <div class="col-md-4 doms">
                <h6 id="top-cardtext">Updated at 07:16AM, Feb 2019</h6>
                
                <div class="row">
                  <div class="col-md-8">
                    <h5>Marketing</h5>
                    <h3>34%</h3>
                  </div>
                  <div class="col-md-4">
                    <h6 id="yrs">2018</h6>
                    <span class="badge mar">Mar</span>
                  </div>
                    <hr>
                </div>

                <div class="row">
                  <div class="col-md-8">
                    <h5>Development</h5>
                    <h3>49%</h3>
                    <hr>
                  </div>
                  <div class="col-md-4">
                    <h6 id="yrs">2018</h6>
                    <span class="badge dvr">DVR</span>
                  </div>
                    <hr>
                </div>
                <div class="row">
                  <div class="col-md-8">
                    <h5>Human Resources</h5>
                    <h3>75%</h3>
                    <hr>
                  </div>
                  <div class="col-md-4">
                    <h6 id="yrs">2018</h6>
                    <span class="badge hnr">H&R</span>
                  </div>
                </div>


                    <h6 id="top-cardtext">Note: These statistics are aggregated over all of your application's users.</h6>


              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="row">
            <div class="col-md-12">
              <div class="back-card">
                <h6 id="sp">Sales Prediction</h6>
              </div>
            </div>
            
            <div class="col-md-12">
            <div class="back-card due">
            <h6 id="sp">Amount Due</h6>
            <h1>$5998</h1>
            <h6 id="top-cardtext">Milestone Completed</h6>
            <h6 id="sp">Payment for next week</h6>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.3.0/Chart.js"></script>
    <script src="js/vue-charts.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.0.3/vue.min.js"></script>

    <script>
   export default{
     data(){
       return{
         datasets: [
           {
             data: [30,70],
             backgroundColor: ["Red", "Purple"]
           }
         ],
         option: {
           title: {
             display: true,
             position: "bottom",
             text: "Fruits"
           }
         }
       };
     }
   };
 </script>
<script src="../Dashboard/dashboard.js"></script>

