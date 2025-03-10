
        <!-- controller level -->
        <div class="column">
          <div class="content">
            <h2 class="title is-4">Controller Level</h2>
            <div class="content has-text-justified"></div>

              <!-- challenge3 controller behavior shift-->
              <div class="columns">
                <div class="column is-half">
                  <p>
                  <strong>Challenge 3: Controller Behavior Shift</strong> IL policy is commonly trained on commanded pose and deployed with low-gain controller.
                  However, the controller behavior may shift during high-speed execution. We propose to train policy using reached pose and leverage high-fidelity controller to track the trajectory precisely.
                </p>
                <div class="centered-image">
                  <img src="static/images/method1_reach_pose_command_pose.png" alt="SAIL Overview" width="100%">
                </div>
              </div>
            </div>
            <!--/ challenge3 controller behavior shift-->

            <!-- challenge4 action scheduling-->
            <div class="columns">
              <div class="column is-half">
                <p>
                  <strong>Challenge 4: System Latency in Control Loop</strong>  System latencies caused by communication and control loop can lead to out-of-distribution inputs to the policy and time-misaligned action commands to the controller.
                  To address this, we propose a novel action scheduling mechanism to handle real-world system latencies.
                </p>
                <div class="centered-image">
                <img src="static/images/method_system_latency.png" alt="SAIL Overview" width="100%">
                </div>
              </div>
            </div>
            <!--/ challenge4 action scheduling-->
          </div>
        </div>


        <!--/ controller level -->


<!-- <section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered">
      <div class="column">
        <div class="content">
          <h2 class="title is-3">SAIL System Overview</h2>
          <p>
            Placeholder 1.
          </p>
          <video id="dollyzoom" autoplay controls muted loop playsinline height="100%">
            <source src="./static/videos/dollyzoom-stacked.mp4"
                    type="video/mp4"> -->
                    <h2>Placeholder 1 Video</h2>
                  </video>
                </div>
              </div>
              <!--/ Visual Effects. -->
        
              <!-- Matting. -->
              <div class="column">
                <h2 class="title is-3">Placeholder 2</h2>
                <div class="columns is-centered">
                  <div class="column content">
                    <p>
                      Placeholder 2ljkljlkjljkl.
                    </p>
                    <video id="matting-video" controls playsinline height="100%">
                      <!-- <source src="./static/videos/matting.mp4"
                              type="video/mp4"> -->
                      <h2>Placeholder 2 Video</h2>
                    </video>
                  </div>
        
                </div>
              </div>
            </div>
            <!--/ Matting. -->
        
            <!-- Animation. -->
            <div class="columns is-centered">
              <div class="column is-full-width">
                <h2 class="title is-3">SAIL System Components Overview</h2>
        
                <!-- Interpolating. -->
                <h3 class="title is-4">Placeholder 4</h3>
                <div class="content has-text-justified">
                  <p>
                    Placeholder 4.
                  </p>
                </div>
                <!-- <div class="columns is-vcentered interpolation-panel">
                  <div class="column is-3 has-text-centered">
                    <img src="./static/images/interpolate_start.jpg"
                         class="interpolation-image"
                         alt="Interpolate start reference image."/>
                    <p>Start Frame</p>
                  </div>
                  <div class="column interpolation-video-column">
                    <div id="interpolation-image-wrapper">
                      Loading...
                    </div>
                    <input class="slider is-fullwidth is-large is-info"
                           id="interpolation-slider"
                           step="1" min="0" max="100" value="0" type="range">
                  </div>
                  <div class="column is-3 has-text-centered">
                    <img src="./static/images/interpolate_end.jpg"
                         class="interpolation-image"
                         alt="Interpolation end reference image."/>
                    <p class="is-bold">End Frame</p>
                  </div>
                </div> -->
                <br/>
                <!--/ Interpolating. -->
        
                <!-- Re-rendering. -->
                <h3 class="title is-4">Placeholder 5</h3>
                <div class="content has-text-justified">
                  <p>
                    Placeholder 5.
                  </p>
                </div>
                <div class="content has-text-centered">
                  <video id="replay-video"
                         controls
                         muted
                         preload
                         playsinline
                         width="75%">
                    <!-- <source src="./static/videos/replay.mp4"
                            type="video/mp4"> -->
                    <h2>Placeholder 5 Video</h2>
                  </video>
                </div>
                <!--/ Re-rendering. -->
        
              </div>
            </div>
            <!--/ Animation. -->
        
          </div>
        </section>
        