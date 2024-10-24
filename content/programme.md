---
title: "CHR2024 Programme"
layouttype: "single" 
---
<!-- CSS for tabs -->
<style>
/* modified from https://codepen.io/markcaron/pen/MvGRYV */
/* interaction */
.tabset > input[type="radio"] {
  position: absolute;
  left: -200vw;
}

.tabset .tab-panel {
  display: none;
}

.tabset > input:first-child:checked ~ .tab-panels > .tab-panel:first-child,
.tabset > input:nth-child(3):checked ~ .tab-panels > .tab-panel:nth-child(2),
.tabset > input:nth-child(5):checked ~ .tab-panels > .tab-panel:nth-child(3),
.tabset > input:nth-child(7):checked ~ .tab-panels > .tab-panel:nth-child(4),
.tabset > input:nth-child(9):checked ~ .tab-panels > .tab-panel:nth-child(5),
.tabset > input:nth-child(11):checked ~ .tab-panels > .tab-panel:nth-child(6) {
  display: block;
}

/*
 Styling
*/
.tabset > label { /* styling of label */
  position: relative;
  display: inline-block;
  padding: 15px 15px 25px;
  border: 1px solid transparent;
  border-bottom: 0;
  cursor: pointer;
  font-weight: 600;
  font-size: 1.2em !important;
}

.tabset > label::after {
  content: "";
  position: absolute;
  left: 15px;
  bottom: 10px;
  width: 22px;
  height: 4px;
  background: #8d8d8d; /* inactive tab: color of line underneath tab*/
}

input:focus-visible + label {
  outline: 2px solid rgba(0,102,204,1);
  border-radius: 3px;
}

.tabset > label:hover,
.tabset > input:focus + label,
.tabset > input:checked + label {
  color: #0B25DA; /* active tab: color of label*/
}

.tabset > label:hover::after,
.tabset > input:focus + label::after,
.tabset > input:checked + label::after {
  background: #0B25DA; /* active tab: color of line underneath tab */
}

.tabset > input:checked + label {
  border-color: #ccc;
  border-bottom: 1px solid #fff;
  margin-bottom: -1px;
}

.tab-panel {
  padding: 30px 0;
  border-top: 1px solid #ccc;
}
</style>
<!-- HTML FOR PROGRAMME -->
Programme for the [pre-conference workshops](#parallel-workshops) on [Tuesday](#tuesday), 3rd December 2024, and the main conference days on [Wednesday](#wednesday), [Thursday](#thursday), and [Friday](#friday), 4th-6th December 2024.

*Please note that all times are in Central European Time (CET)*

<!-- DAYS -->
<div class="tabset">

  <!-- button creation -->
  <!-- TUE -->
  <input type="radio" name="tabset" id="tuesday" aria-controls="tuesday">
  <label for="tuesday">Tuesday</label>
  <!-- WED -->
  <input type="radio" name="tabset" id="wednesday" aria-controls="wednesday" checked>
  <label for="wednesday">Wednesday</label>
  <!-- THUR -->
  <input type="radio" name="tabset" id="thursday" aria-controls="thursday">
  <label for="thursday">Thursday</label>
  <!-- FRI -->
  <input type="radio" name="tabset" id="friday" aria-controls="friday">
  <label for="friday">Friday</label>
  
  <!-- content -->
  <div class="tab-panels">
  <section id="tuesday" class="tab-panel" alt="tab showing the schedule for tuesday">
   <h2 id="overview-tue" alt="Overview of Tuesday" style="font-weight:bold;">Tuesday, December 3, 2024 (Pre-conference workshops)</h2>
   <p>
    <ul>
      <li>09:00-12:30: <a href="#parallel-workshops"><strong>Workshop sessions</strong></a></li>
      <li>12:30-13:30: <em>Lunch</em></li>
      <li>13:30-17:00: <a href="#parallel-workshops"><strong>Workshop sessions</strong></a></li>
    </ul>    
   </p>
   <h3 id="parallel-workshops" style="font-weight:bold; font-size:2em;">Parallel Workshops<h3>
   <h3> Digital Methods for Mythological Research </h3>
   <p style="font-size:1em">
    dm4myth aims to bring together researchers from various disciplines who are interested in studying myths with digital tools and methods.
    We welcome contributions from various disciplines, such as (but not limited to) Ancient Near Eastern Studies, Religious Studies, Classical Studies/Classical Philology, Art History.
    The primary focus of this workshop is to explore the narrative material of mythological stories, underlying belief systems, and the multifaceted representation of characters in mythological contexts using digital methods.
    The full-day workshop is targeted at scholars who work on interdisciplinary research questions, which involve mythological (and derivative) topics and the application or development of computer science methods and algorithms.
    We welcome participants from all stages of their academic career, from (under-)graduate students to early career researchers and senior researchers. (<a href="https://dm4myth.github.io">https://dm4myth.github.io</a>)
   </p>
   <p>
   <h3>Analysing the Reception of Fiction Novels Across Languages</h3>
    <p style="font-size:1em">
    This workshop delves into the intersection of cultural practices and the digital sphere through a hands-on exploration of multilingual fiction book reviewing. 
    It offers participants an immersive experience, guiding them through the full research workflow of computational reader response studies, using book reviews and online comments as proxies for reception.
    Scheduled as four sessions, the workshop provides data and addresses key theoretical, methodological, and interpretive challenges to give participants a comprehensive understanding of the process. It is particularly suited for early career researchers, while senior researchers are also encouraged to attend and engage in discussions on theory and methodology. 
    Participants will gain practical experience with advanced NLP methods, statistical modeling, and computational approaches to reader response studies. Basic familiarity with Python is recommended.
    (<a href="https://igelsociety.github.io/CHR2024-book-reviews-workshop/">https://igelsociety.github.io/CHR2024-book-reviews-workshop/</a>)
    <br>
    <br>
    <i> Note: A maximum of 30 people can attend this workshop, and registered participants of the conference who indicated an interest in this workshop are selected on a first-come-first-serve basis.</i>
   </p>
   </p>
  </section>
  <!-- WED -->
    <section id="wednesday" class="tab-panel" alt="tab showing the schedule for wednesday">
      <h2 id="overview-wed" alt="Overview of Wednesday" style="font-weight:bold;">Wednesday, December 4, 2024 (Day 1)</h2>
      <p>
      <ul>
          <li>9:00-11:00: <em>Registration and coffee</em></li>
          <li>11:15-11:30: <em>CHR opening words</em></li>
          <li>11:30-12:30: <strong>Keynote</strong></li>
          <li>12:30-13:30: <em>Lunch</em></li>
          <li>13:30-15:00: <a href="#session1"><strong>Session 1</strong></a> <!-- NB change to #session-1 etc. when those are announced --></li>
          <li>15:00-15:30: <em>Coffee Break</em></li>
          <li>15:30-17:00: <a href="#session2"><strong>Session 2</strong></a></li>
          <li>17:00: Opening reception</li>
      </ul>
      </p>
      <h3 style="font-weight:bold; font-size:2em;">Sessions<h3>
      <h3 id="session1" alt="Session 1" style="font-weight:bold;">Session 1 (13.30-15.00)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
      <h3 id="session2" alt="Session 2" style="font-weight:bold;">Session 2 (15.30-17.00)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
  </section>
  <!-- THUR -->
    <section id="thursday" class="tab-panel" alt="tab showing the schedule for thursday">
      <h2 id="overview-thu" alt="Overview of Thursday" style="font-weight:bold;">Thursday, December 5, 2024 (Day 2) </h2>
      <p>
      <ul>
      <li>09:00-10:30: <a href="#lightning-talks"><strong>Lightning talks session</strong></a></li>
      <li>10:30-11:00: <em>Coffee break</em></li>
      <li>11:00-12:30: <a href="#session3"><strong>Session 3</strong></a></li>
      <li>12:30-13:30: <em>Lunch</em></li>
      <li>13:30-15:00: <a href="#session4"><strong>Session 4</strong></a></li>
      <li>15:00-15:30: <em>Coffee break</em></li>
      <li>15:30-17:00: <a href="#session5"><strong>Session 5</strong></a></li>
      <li>17:00: <em>Poster walk-around</em></li>
      <li>20:00: <em>Conference dinner</em></li>
      </ul>
      </p>
      <h3 style="font-weight:bold; font-size:2em;">Sessions<h3>
      <h3 id="session3" alt="Session 3" style="font-weight:bold;">Session 3 (11.00-12.30)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
      <h3 id="session4" alt="Session 4" style="font-weight:bold;">Session 4 (13.30-15.00)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
      <h3 id="session5" alt="Session 5" style="font-weight:bold;">Session 5 (15.30-17.00)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
    </section>
    <!-- FRI -->
    <section id="friday" class="tab-panel" alt="tab showing the schedule for friday">
      <h2 id="overview-fri" alt="Overview of Friday" style="font-weight:bold;">Friday, December 6, 2024 (DAY 3)</h2>
      <p>
        <ul>
          <li>09:00-10:00: <strong>Keynote</strong></li>
          <li>10:00-10:30: <em>Coffee break</em></li>
          <li>10:30-12:00: <a href="#session6"><strong>Session 6</strong></a></li>
          <li>12:00-13:00: <em>Lunch</em></li>
          <li>13:00-14:30: <a href="#session7"><strong>Session 7</strong></a></li>
          <li>14:30-15:00: <em>Coffee break</em></li>
          <li>15:00-16:30: <a href="#session8"><strong>Session 8</strong></a></li>
          <li>16:30-17:00: <em>Award ceremony, concluding remarks</em></li>
        </ul>
      </p>
      <h3 style="font-weight:bold; font-size:2em;">Sessions<h3>
      <h3 id="session6" alt="Session 6" style="font-weight:bold;">Session 6 (10.30-12.00)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
      <h3 id="session7" alt="Session 7" style="font-weight:bold;">Session 7 (13.00-14.30)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
      <h3 id="session8" alt="Session 8" style="font-weight:bold;">Session 8 (15.00-16.30)</h3>
      <p style="font-size:1.1em">
      TBA
      </p>
    </section>
  
  </div>
  <!-- FRI -->
  
</div>


<!-- JS for making tabs and sections inside tabs linkable -->
<script>
function activateTabFromHash() {
    // get the current hash from the URL
    var hash = window.location.hash;
    if (hash) {
        // remove the '#' character
        var id = hash.substring(1);

        // first, try to find a radio button (tab control) with that ID
        var tabRadio = document.getElementById(id);
        if (tabRadio && tabRadio.name === 'tabset') {
            // activate the corresponding tab
            tabRadio.checked = true;
        } else {
            // if not found, try to find an element within a tab panel
            var targetElement = document.getElementById(id);
            if (targetElement) {
                // find the closest ancestor with class 'tab-panel'
                var tabPanel = targetElement.closest('.tab-panel');
                if (tabPanel) {
                    // get the id of the tab panel
                    var panelId = tabPanel.id;
                    // find the radio button whose aria-controls matches the panel id
                    var tabRadio = document.querySelector('input[name="tabset"][aria-controls="' + panelId + '"]');
                    if (tabRadio) {
                        // activate the corresponding tab
                        tabRadio.checked = true;
                    }
                }
            }
        }
    }
}

document.addEventListener("DOMContentLoaded", function() {
    activateTabFromHash();

    // update the URL hash when a new tab is selected
    var radios = document.querySelectorAll('.tabset > input[type="radio"]');
    radios.forEach(function(radio) {
        radio.addEventListener('change', function() {
            if (this.checked) {
                // update the URL hash to the radio button's ID
                history.replaceState(null, null, '#' + this.id);
            }
        });
    });
});

// listen for hash changes (e.g., when clicking on links to anchors)
window.addEventListener('hashchange', function() {
    activateTabFromHash();
});
</script>



