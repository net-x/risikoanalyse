<template>
  <section>
    <div class="wrapper">
      <!-- Sidebar Holder -->
      <nav id="sidebar">
        <div class="sidebar-header text-center">
          <img 
            src="~assets/images/zurich-logo.png" 
            alt="logo">
        </div>
        <ul class="list-unstyled components">
          <li>
            <a href="form/1">Unternehmensdaten</a>
          </li>
          <li>
            <a href="form/2">Haftungsrisiken</a>
          </li>
          <li>
            <a href="form/3">Gebäude-Werte</a>
          </li>
          <li>
            <a href="form/4">Inhalt-Werte</a>
          </li>
          <li>
            <a href="form/5">Elektronik/Maschinen-Werte</a>
          </li>
          <li>
            <a href="form/6">Unterbrechung Ihres Betriebes</a>
          </li>
          <li>
            <a href="form/7">Kosten bei Rechtsangelegenheiten</a>
          </li>
          <li>
            <a href="form/8">Transporte</a>
          </li>
          <li>
            <a href="form/9">Kfz-Risiken</a>
          </li>
          <li class="active">
            <a href="form/10">Spezial-Risiken</a>
          </li>
          <li>
            <a href="form/11">Mitarbeiter</a>
          </li>
          <li class="active">
            <a href="form/12">Belegschaft / Inhabers / GGf / etc.</a>
          </li>
          <li>
            <a href="form/13">Offene Punkte und weiteres Vorgehen</a>
          </li>
        </ul>
        <ul class="list-unstyled CTAs">
          <li>
            <a 
              href="../analyse"
              class="resume mt-3"><i class="fas fa-sliders-h"/> Analyse</a>
          </li>
        </ul>
      </nav>
      <!-- Page Content Holder -->
      <div id="content">
        <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light">
          <div class="container-fluid">
            <button 
              id="sidebarCollapse" 
              type="button" 
              class="navbar-btn">
              <span/>
              <span/>
              <span/>
            </button>
            <button 
              class="btn btn-dark d-inline-block d-lg-none ml-auto" 
              type="button" 
              data-toggle="collapse" 
              data-target="#navbarSupportedContent" 
              aria-controls="navbarSupportedContent" 
              aria-expanded="false" 
              aria-label="Toggle navigation">
              <i class="fas fa-align-justify"/>
            </button>
            <ul class="nav navbar-nav navbar-expand ml-auto">
              <li class="nav-item">
                <a 
                  class="nav-link" 
                  href="selectuser"><i class="fas fa-users"/> Kunden</a>
              </li>
              <li class="nav-item">
                <a 
                  class="nav-link" 
                  href="index"><i class="fas fa-sign-out-alt"/> Abmelden</a>
              </li>
            </ul>
          </div>
        </nav>
        <div class="container-fluid">
          <div class="row">
            <div class="col-10">
              <h3>Absicherung Ihrer Spezial-Risiken</h3>
            </div>
            <div class="col-2 float-sm-right text-right">
              <a 
                href="form/11" 
                class="btn btn-success">Speichern</a>
            </div>
          </div>
          <div class="line"/>
          <form>
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Wie hoch schätzen Sie das Risiko von Zahlungsausfällen durch Ihre gewerblichen Kunden ein?</label>
                    <textarea 
                      id="place" 
                      type="text-area" 
                      class="form-control" 
                      rows="2" 
                      placeholder=""/>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Werden von Ihren Kunden Bürgschaften eingefordert?</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline1" 
                                type="radio" 
                                name="customRadioInline1" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline1">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline2" 
                                type="radio" 
                                name="customRadioInline1" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline2">nein</label>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Welche Folgen können Datenklau und Datenmissbrauch bei Ihnen haben (Cyber-Attacken)?</label>
                    <textarea 
                      id="place" 
                      type="text-area" 
                      class="form-control" 
                      rows="2" 
                      placeholder=""/>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Wie sind Sie und Ihre Mitarbeiter gegen die Folgen eines Unfalls abgesichert?</label>
                    <textarea 
                      id="place" 
                      type="text-area" 
                      class="form-control" 
                      rows="2" 
                      placeholder=""/>
                  </div>
                </div>
              </div>
            </div>
            <div class="form-group">
              <div class="card">
                <div class="card-body">
                  <label for="place">Notizen</label>
                  <textarea 
                    id="place" 
                    type="text-area" 
                    class="form-control" 
                    rows="3" 
                    placeholder=""/>
                </div>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
