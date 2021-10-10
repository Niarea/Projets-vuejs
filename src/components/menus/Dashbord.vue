<template>
  <div class="columns">
    
        <!-- Début colonne de gauche -->
    <div class="column is-one-fifth">
      <div id="parentx">
        <vs-sidebar parent="body" default-index="1"  color="primary" class="sidebarx" spacer v-model="sidebar_right">
          <div class="header-sidebar" slot="header">
              <img src="../../assets/tun.jpeg" alt="">
          </div>
       
            <vs-sidebar-item index="1" icon="question_answer">
              Dashboard
            </vs-sidebar-item>
            <vs-sidebar-group title="Magasin">
              <vs-sidebar-item index="2.1" icon="store">
                Magasin
              </vs-sidebar-item>
              <vs-sidebar-item index="2.2" icon="nature_people">
                Nature
              </vs-sidebar-item>
              <vs-sidebar-item index="2.3" icon="style">
                Style
              </vs-sidebar-item>
            </vs-sidebar-group>
            <vs-sidebar-item index="2" icon="gavel">
              Historique
            </vs-sidebar-item>
            <vs-sidebar-item index="3" icon="https">
              Sécurité
            </vs-sidebar-item>
            <vs-sidebar-item index="4" icon="help">
              Aide
            </vs-sidebar-item>
            <vs-sidebar-item index="5" icon="verified_user">
            Configurations
          </vs-sidebar-item>
          <vs-sidebar-item index="6" icon="account_box">
            Profile
          </vs-sidebar-item>
        </vs-sidebar>
      </div>
    </div>
    <!-- Fin colonne de gauche -->

    <!-- Début colonne du milieu -->
    <div class="column centre">
      <div class="dashbord">
        <div class="columns">
          <div class="column is-11">
              <span style="font-weight:bold; font-size: 20px">Dashbord</span>
          </div>

          <div class="column is-1">
            <vs-button size="large" disabled color="primary" type="border" icon="search" class="icon"></vs-button>
          </div>
        </div>
      </div>
      

      <div class="orange">
          <div class="columns">
            <div class="column">
                <p class="tunnailes">Bienvenue chez Tunnailes !</p>
                <p>
                Nous allons tunner vos ailes pour mieux planer.
                Controlons votre image avec le pouvoir du digitale
                </p>
            </div>
            
            <div class="column">
              <img src="../../assets/img-box.png" alt="" class="img-box">
            </div>
        </div>
      </div>

      <div class="dashbord">
        <div class="columns dashbord">
          <div class="column is-6">
            <div class="card">
              <div class="card-content" style="text-align:center">
                <table class="table">
                  <thead class="no-border">
                    <tr>
                      <th>Latest results</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th>More  =></th>
                      <th></th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <th class="td1">Unit s - Technology</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="25" color="danger"></vs-progress></th>
                      <th style="color:red">25%</th>
                    </tr>
                    <tr>
                      <th class="td1">Unit 12 - Ecology</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="44" color="primary">primary</vs-progress></th>
                      <th  style="color:blue">44%</th>
                    </tr>
                    <tr>
                      <th class="td1">Unit 9 - <span>Real estate</span></th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="40" color="primary"></vs-progress></th>
                      <th  style="color:blue">40%</th>
                    </tr>
                    <tr>
                      <th class="td1">Unit 8 - Education</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="15" color="danger"></vs-progress></th>
                      <th  style="color:red">15%</th>
                    </tr>
                    <tr>
                      <th class="td1">Unit 9 - School</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="74" color="primary"></vs-progress></th>
                      <th  style="color:blue">74%</th>
                    </tr>
                    <tr>
                      <th class="td1">Unit 10 - market</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="69" color="warning"></vs-progress></th>
                      <th  style="color: rgba(255, 204, 0, 0.933)">69%</th>
                    </tr>
                    <tr>
                      <th class="td1">Unit 16 - Job market</th>
                      <th></th>
                      <th></th>
                      <th></th>
                      <th><vs-progress :height="3" :percent="80" color="success"></vs-progress></th>
                      <th  style="color: rgba(144, 194, 46, 0.898)">80%</th>
                    </tr>
                  </tbody>
                </table>
              </div>
          </div>
        </div>

        <div class="column is-6">
          <div class="card">
            <div class="card-content">
              <table class="table">
                <thead class="no-border">
                  <tr>
                    <th>Time spent on learning</th>
                    <th>Last week</th>
                  </tr>
                </thead>
                <tbody class="tbody1 no-border">
                  <tr>
                    <td class="td1">Sun</td>
                    <td class="td2"><vs-progress :height="3" :percent="46" color="danger"></vs-progress></td>
                  </tr>
                  <tr>
                    <td class="td1">Sat</td>
                    <td class="td2"><vs-progress :height="3" :percent="67" color="primary"></vs-progress></td>
                  </tr>
                  <tr>
                     <td class="td1">Fri</td>
                    <td class="td2"><vs-progress :height="3" :percent="70" color="warning"></vs-progress></td>
                  </tr>
                  <tr>
                    <td class="td1">Thu</td>
                    <td class="td2"><vs-progress :height="3" :percent="29" color="success"></vs-progress></td>
                  </tr>
                  <tr>
                    <td class="td1">Wed</td>
                    <td class="td2"><vs-progress :height="3" :percent="11" color="primary"></vs-progress></td>
                  </tr>
                  <tr>
                    <td class="td1">Tue</td>
                    <td class="td2"><vs-progress :height="3" :percent="74" color="danger"></vs-progress></td>
                  </tr>
                  <tr>
                    <td class="td1">Mon</td>
                    <td class="td2"><vs-progress :height="3" :percent="20" color="primary"></vs-progress></td>
                  </tr>
                </tbody>
              </table>

              <div class="columns">
                <div class="column">
                  <span><vs-progress :height="3" :percent="5" color="danger"></vs-progress>Vocabulary</span>
                </div>

                <div class="column">
                  <span><vs-progress :height="3" :percent="5" color="primary"></vs-progress>Grammar</span>
                </div>

                <div class="column">
                  <span><vs-progress :height="3" :percent="5" color="warning"></vs-progress>Listening</span>
                </div>

                <div class="column">
                  <span><vs-progress :height="3" :percent="5" color="success"></vs-progress>Writing</span>
                </div>
              </div>
            </div>
          </div>
          
        </div>
        </div>
      </div>
      <div class="columns">
          <div class="column">
            <span style="float: left; font-weight:bold; font-size: 14px">Your courses</span>
          </div>
          <div class="column">
            <span style="float: right; font-weight:bold; margin-right: 16px; font-size: 14px">More</span>
          </div>
        </div>
        <div class="columns box-bas">
          <div class="column box-bas1">
            <div  class="columns">
              <div class="column">
                <vs-button disabled color="rgba(188, 141, 232, 0.453)">B2</vs-button>
              </div>
              <div class="column">
                <p style="color:white" class="phrase">English</p><br>
                <p style="color:white; font-weight:bold" class="phrase">Grammar</p>
              </div>
              <div class="column">
                <vs-button disabled color="rgba(188, 141, 232, 0.453)" style="margin-top: 25px">=></vs-button>
              </div>
            </div>
          </div>

          <div class="column box-bas2">
            <div  class="columns">
              <div class="column">
                <vs-button disabled color="rgba(151, 97, 201, 0.57)">B2</vs-button>
              </div>
              <div class="column">
                <span style="color:white" class="phrase">French</span><br><br>
                <p style="color:white; font-weight:bold">Phrasal</p>
              </div>
              <div class="column">
                <vs-button disabled color="rgba(151, 97, 201, 0.57)" style="margin-top: 25px">=></vs-button>
              </div>
            </div>
          </div>
          
          <div class="column box-bas3">
            <div  class="columns">
              <div class="column">
                <vs-button disabled color="rgba(255, 0, 0, 0.145)">C1</vs-button>
              </div>
              <div class="column">
                <span style="color:white" class="phrase">Spanish</span><br><br>
                <p style="color:white; font-weight:bold">Vocabulary</p>
              </div>
              <div class="column">
                <vs-button disabled color="rgba(255, 0, 0, 0.145)" style="margin-top: 25px">=></vs-button>
              </div>
            </div>
          </div>
        </div> 
      </div>
      <!-- Fin colonne du milieu -->

      <!-- Début colonne de droite -->
      <div class="column is-one-fifth">

        <div id="parentx">
          <vs-sidebar position-right parent="body" default-index="1"  color="primary" class="sidebarx" spacer v-model="sidebar_left">
            <div class="header-sidebar header" slot="header" style="padding-bottom: 50px">
              <div class="columns">
                <div class="column">
                  <span style="font-weight: bold; flex: left; margin-left: 10px; font-size: 20px">Déconnexion</span>
                </div>
                <div class="column">
                  <span style="flex: right"><vs-button color="dark" type="border" icon="logout"></vs-button></span>
                </div>
              </div>
              <div>
                <span><vs-avatar  size="70px"/> <vs-button color="primary" icon="add" class="bouton"></vs-button></span>
              </div>
              <h4 style="font-weight:bold">
                Niaré Adama
              </h4>
            </div>

            <vs-sidebar-item index="1">
              <div>
                <button class="button" title="Disabled button" disabled style="float: left; font-weight:bold">B2</button>
              </div>
              <div style="float: right; margin-left: 100px">
                <span>English<vs-progress :height="3" :percent="70" color="danger"></vs-progress></span>
              </div>
            </vs-sidebar-item>

            <vs-sidebar-item index="2">
              <div>
                <button class="button" title="Disabled button" disabled style="float: left; font-weight:bold">C2</button>
              </div>
              <div style="float: right; margin-left: 100px">
                <span>Spanish</span> <vs-progress :height="3" :percent="40" color="success"></vs-progress>
              </div>
            </vs-sidebar-item>

            <vs-sidebar-item index="3">
              <div>
                <button class="button" title="Disabled button" disabled style="float: left; font-weight:bold">C2</button>
              </div>
              <div style="float: right; margin-left: 10px">
                <p>
                  <span style="float:left">Eng - Vocabulary test</span> <span style="float:left">02 juillet 2021</span>
                </p>
              </div>
            </vs-sidebar-item>
            <vs-sidebar-item index="4">
              <div>
                <vs-button disabled radius color="primary" type="border" icon="inbox"></vs-button>
              </div>
              <div style="float: right; margin-left: 10px">
                <p>
                  <span style="float:left">Eng - Send grammar homework</span> <span style="float:left">02 juillet 2021</span>
                </p>
              </div>
            </vs-sidebar-item>
            <vs-sidebar-item index="5" >
              <div>
                <vs-button disabled radius color="primary" type="border" icon="inbox"></vs-button>
              </div>
              <div style="float: right; margin-left: 10px">
                <p>
                  <span style="float:left; font-weight: bold">Spanish - Send essey</span> <span style="float:left">02 juillet 2021</span>
                </p>
              </div>
            </vs-sidebar-item>

          </vs-sidebar>
        </div>
    </div>
    <!-- Fin colonne de droite -->

  </div>
</template>


<script>
export default {
  data:()=>({
    sidebar_right:true,
    sidebar_left:true,
  })
}
</script>
