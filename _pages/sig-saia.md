---
layout: page
title: SIG-SAIA
permalink: /sig-saia/
description: Special Interest Group in Spatial Acoustics and Immersive Audio
nav: true
nav_order: 6
---

The Special Interest Group in Spatial Acoustics and Immersive Audio (SIG-SAIA) brings together researchers, practitioners and end-users from academia and industry who work on the spatial side of audio and acoustics.

SIG-SAIA started as a special interest group within the [UK Acoustics Network (UKAN)](https://acoustics.ac.uk/) and now runs as an independent group.

<img src="/assets/img/SIG-SAIA.jpg" alt="Dome of loudspeakers" style="display: block; width: 100%; aspect-ratio: 3 / 1; object-fit: cover; object-position: center 25%; border-radius: 0.25rem; margin-bottom: 1.5rem;">

## Join the mailing list

The SIG-SAIA mailing list is a Google Group. Members receive announcements about meet-ups, seminars, workshops, jobs and calls for papers, and can post to the list.

- **With a Google account:** go to [groups.google.com/g/sig-saia](https://groups.google.com/g/sig-saia) and click **Join group**.
- **Without a Google account:** send a blank email to [sig-saia+subscribe@googlegroups.com](mailto:sig-saia+subscribe@googlegroups.com) from the address you want to use, then reply to the confirmation email.

To leave, send a blank email to [sig-saia+unsubscribe@googlegroups.com](mailto:sig-saia+unsubscribe@googlegroups.com) or use the link at the bottom of any list email.

## What we cover

- **Acquisition:** microphone arrays, beamforming, direction-of-arrival estimation and 6DoF sound field capture.
- **Rendering:** loudspeaker arrays, headphone and binaural rendering, and acoustic augmented reality.
- **Perception:** spatial hearing, listening experiments and binaural auditory models.
- **Applications:** immersive audio production, AR/VR for audiology research and clinical use, auditory training and auditory displays.

## What we do

We run topic-focused meet-ups for members, a yearly workshop or showcase, and a seminar series. We also organise joint events with groups such as Immerse UK, the AES, the IEEE and the Institute of Acoustics, along with training events aimed at early-career researchers.

## Coordinators

- [Prof Lorenzo Picinali](https://profiles.imperial.ac.uk/l.picinali), Imperial College London
- [Dr Aidan Hogg](https://aidanhogg.uk/), Queen Mary University of London
- [Prof Filippo Fazi](https://www.southampton.ac.uk/vaae/about/staff/fmf205_ffazi.page), University of Southampton (ISVR)
- [Dr Jacob Hollebon](https://www.linkedin.com/in/jakehollebon/), Audioscenic

## Jobs
 
<div class="job" data-closes="2026-12-08">
  <h3>Postdoctoral Research Associate – Spatial Hearing and Machine Learning</h3>
  <p class="job-meta">Queen Mary University of London. Closing date: 8 December 2026</p>
  <p>A 36-month position working with Dr Aidan Hogg on the EPSRC-funded project <em>Spatial Hearing Augmentation to Improve Hearing Assistive Technology</em>, which investigates whether enhanced artificial spatial hearing cues can improve sound localisation, speech understanding in noise and situational awareness for people with hearing loss.</p>
  <details>
    <summary>Details</summary>
    <ul>
      <li><strong>Department:</strong> School of Electronic Engineering and Computer Science, Centre for Multimodal AI</li>
      <li><strong>Contract:</strong> Full-time, fixed-term (36 months)</li>
      <li><strong>Salary:</strong> £39,187–£47,550 per annum</li>
      <li><strong>Reference:</strong> 11997</li>
    </ul>
    <p>The successful candidate will develop personalised head-related transfer function (HRTF) models, apply machine learning and auditory-model optimisation techniques, and design perceptual experiments to evaluate spatial hearing augmentation, in collaboration with Imperial College London and Eargym Ltd.</p>
    <p>We are looking for candidates with a PhD (or close to completion), or equivalent research experience, in acoustics, audio signal processing, machine learning, hearing science or a related field. Experience with spatial audio, HRTFs, Python/MATLAB and machine learning is particularly relevant.</p>
  </details>
  <p class="job-apply"><a href="https://qmul-jobs.tal.net/vx/lang-en-GB/mobile-1/appcentre-1/brand-4/user-155681/candidate/so/pm/1/pl/3/opp/11997-Postdoctoral-Research-Associate/en-GB">Apply on the Queen Mary jobs site</a>. For informal enquiries, email <a href="mailto:a.hogg@qmul.ac.uk">a.hogg@qmul.ac.uk</a>.</p>
</div>
<p class="no-jobs" hidden>There are no open positions at the moment. New vacancies are announced on the mailing list.</p>
<script>
  (function () {
    var now = new Date();
    var open = 0;
    document.querySelectorAll(".job[data-closes]").forEach(function (job) {
      var closes = new Date(job.getAttribute("data-closes") + "T23:59:59");
      if (now > closes) { job.hidden = true; } else { open++; }
    });
    if (!open) { document.querySelector(".no-jobs").hidden = false; }
  })();
</script>


## Upcoming events
 
There are no upcoming events at the moment. New meet-ups are announced on the [mailing list](#join-the-mailing-list).
 
<!-- To add an event, replace the sentence above with a block like this one:
<div class="event">
  <h3>Event title</h3>
  <p class="event-meta">Venue, date</p>
  <p>A sentence or two about the event and how to register.</p>
</div>
-->

## Past meet-ups

Our in-person meet-ups combine short member talks with visits to labs, venues, and industry partners.

<style>
  article h2 { margin-top: 2.25rem; margin-bottom: 0.75rem; }
  .meetup { margin-top: 2rem; }
  .meetup + .meetup { margin-top: 2.5rem; padding-top: 2.5rem; border-top: 1px solid var(--global-divider-color); }
  .meetup-body { margin-top: 1.25rem; }
  .meetup-body h3 { font-size: 1.15rem; margin: 0 0 0.3rem; }
  .meetup-date { color: var(--global-text-color-light); margin-bottom: 0.9rem; }
  .meetup-text { margin-bottom: 1.1rem; }
  .meetup details + details { margin-top: 0.6rem; }
  .meetup summary { cursor: pointer; color: var(--global-theme-color); }
  .meetup details ul { margin: 0.9rem 0 0.5rem; font-size: 0.9rem; }
  .meetup details li { margin-bottom: 0.45rem; }
  .meetup details li.meetup-sub { list-style: none; margin: 0.9rem 0 0.45rem -1rem; font-weight: bold; }
  .meetup-credit { font-size: 0.9rem; color: var(--global-text-color-light); margin: 0.75rem 0 0.5rem; }
  .meetup-photos { margin-top: 0.9rem; }
  .job, .event { border: 1px solid var(--global-divider-color); border-radius: 0.5rem; padding: 1.25rem 1.5rem; margin-bottom: 1rem; }
  .job h3, .event h3 { font-size: 1.15rem; margin: 0 0 0.3rem; }
  .job-meta, .event-meta { color: var(--global-text-color-light); margin-bottom: 0.9rem; }
  .job summary { cursor: pointer; color: var(--global-theme-color); }
  .job details ul { margin: 0.9rem 0 0.5rem; }
  .job details li { margin-bottom: 0.45rem; }
  .job-apply { margin: 1rem 0 0; }
  .meetup-photos img, .meetup-photos video { width: 100%; margin-bottom: 1.5rem; }
  @media (min-width: 576px) {
    .meetup-image { padding-right: 1.5rem; }
    .meetup-body { margin-top: 0; padding-left: 1.5rem; }
  }
</style>
 
<div class="meetup">
  <div class="row">
    <div class="col-sm-5 meetup-image">
      <img src="/assets/img/Yamaha_2026.jpeg" alt="Group photo at Yamaha Music London, November 2026" class="img-fluid rounded z-depth-1" loading="lazy">
    </div>
    <div class="col-sm-7 meetup-body">
      <h3>Queen Mary University of London and Yamaha Music London</h3>
      <p class="meetup-date">24 November 2026</p>
      <p class="meetup-text">Eight short talks on topics from auraldiversity and personalised HRTFs to loudspeaker layouts, room acoustics and immersive audio authoring, followed by a Sound xR session at Yamaha Music London hosted by Tom Rundle.</p>
      <details>
        <summary>Programme</summary>
        <ul>
          <li class="meetup-sub">At Queen Mary (10-minute talks, including questions)</li>
          <li><strong>11:45–12:30</strong> Arrival and lunch</li>
          <li><strong>12:30–12:35</strong> Welcome and introduction, Aidan Hogg (Queen Mary University of London)</li>
          <li><strong>12:35–12:45</strong> John Levack Drever (Cambridge Digital Humanities, University of Cambridge), <em>Whose Spatial Hearing? Auraldiversity and the Limits of Immersive Audio</em></li>
          <li><strong>12:45–12:55</strong> Rashad Al-Dahiri (Queen Mary University of London), <em>Individualised Head-Related Transfer Function Generation via Geometric Parameterisation of Synthetic Pinnae</em></li>
          <li><strong>12:55–13:05</strong> Philip Jackson (University of Surrey), <em>Design of the Aurora3 loudspeaker arrangement</em></li>
          <li><strong>13:05–13:15</strong> Rapolas Daugintis (University of Surrey), <em>Perceptually-driven optimisation of loudspeaker-based spatial audio</em></li>
          <li><strong>13:15–13:25</strong> Nara Hahn (University of Southampton), <em>Sound field diffuseness estimation in the spherical harmonic domain</em></li>
          <li><strong>13:25–13:35</strong> Orchisama Das (King’s College London), <em>Physics-Inspired Delay Networks for Auralisation of Room Acoustics</em></li>
          <li><strong>13:35–13:45</strong> Yuke Liu (Queen Mary University of London), <em>A Benchmark of World Models’ Capabilities from Spatial Audio Perspective: A Preliminary Design</em></li>
          <li><strong>13:45–13:55</strong> Daniel Jones (Independent), <em>Authoring immersive audio environments with Hodr and SignalFlow</em></li>
          <li><strong>13:55–14:00</strong> Discussion of future plans for the group, Lorenzo Picinali (Imperial College London)</li>
          <li><strong>14:00–14:15</strong> Group photo and wrap-up</li>
          <li class="meetup-sub">At Yamaha Music London</li>
          <li><strong>15:00–16:30</strong> Sound xR session hosted by Tom Rundle: an introduction to the Yamaha product range, two guest speakers on how they use Sound xR in their work, and a demonstration with questions and discussion</li>
        </ul>
        <p class="meetup-credit">Organised by Aidan Hogg, with the other SIG coordinators.</p>
      </details>
      <details>
        <summary>Photos and video</summary>
        <div class="row meetup-photos">
          <div class="col-6">
            <img src="/assets/img/Yamaha_2026_qm_talk.jpg" alt="A talk at Queen Mary University of London" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/Yamaha_2026_sound_xr_session.jpg" alt="The Sound xR session at Yamaha Music London" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/Yamaha_2026_sound_xr.jpg" alt="Attendees exploring the How To Build An Orchestra installation at Yamaha Music London" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/Yamaha_2026_sound_xr_software.jpg" alt="Sound xR software on screen in a Yamaha demo room" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <video src="/assets/img/Yamaha_2026_sound_xr.mp4" poster="/assets/img/Yamaha_2026_sound_xr_poster.jpg" controls preload="none" playsinline class="rounded" aria-label="Video of the How To Build An Orchestra installation at Yamaha Music London"></video>
          </div>
        </div>
        <p class="meetup-credit">Some photos by Chin-Yun Yu.</p>
      </details>
    </div>
  </div>
</div>
<div class="meetup">
  <div class="row">
    <div class="col-sm-5 meetup-image">
      <img src="/assets/img/kef_2025.webp" alt="Group photo at the KEF Music Gallery, February 2025" class="img-fluid rounded z-depth-1" loading="lazy">
    </div>
    <div class="col-sm-7 meetup-body">
      <h3>KEF Music Gallery, London</h3>
      <p class="meetup-date">20 February 2025</p>
      <p class="meetup-text">A tour of the KEF Music Gallery and listening sessions in its demo rooms, with the KEF team sharing their loudspeaker design expertise.</p>
      <details>
        <summary>Programme</summary>
        <ul>
          <li><strong>10:00–10:15</strong> Tea and coffee</li>
          <li><strong>10:15–10:30</strong> Welcome and participant introductions</li>
          <li><strong>10:30–11:30</strong> KEF Music Gallery tour</li>
          <li><strong>11:30–12:30</strong> Listening sessions in the Living Room and UER</li>
          <li><strong>12:30–13:30</strong> Lunch</li>
          <li><strong>13:30–15:30</strong> Group activities</li>
          <li><strong>15:30–16:00</strong> Wrap-up and Q&amp;A</li>
        </ul>
        <p class="meetup-credit">Organised by Filippo Fazi, with the other SIG coordinators.</p>
      </details>
      <details>
        <summary>Photos</summary>
        <div class="row meetup-photos">
          <div class="col-6">
            <img src="/assets/img/kef_2025_gallery_tour.jpg" alt="Attendees touring the KEF Music Gallery" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/kef_2025_demo_room.jpg" alt="Attendees in a KEF demo room" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/kef_2025_equipment_racks.jpg" alt="A member of the KEF team explaining a bank of equipment racks" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/image3-scaled.webp" alt="A listening room at the KEF Music Gallery" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/kef_2025_living_room.jpg" alt="A listening session in the KEF Living Room" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/kef_2025_afternoon_talk.jpg" alt="A presentation during the afternoon session" class="img-fluid rounded" loading="lazy">
          </div>
        </div>
        <p class="meetup-credit">Some photos by Chin-Yun Yu.</p>
      </details>
    </div>
  </div>
</div>
<div class="meetup">
  <div class="row">
    <div class="col-sm-5 meetup-image">
      <img src="/assets/img/ROH_2024.jpg" alt="Group photo at Queen Mary University of London, May 2024" class="img-fluid rounded z-depth-1" loading="lazy">
    </div>
    <div class="col-sm-7 meetup-body">
      <h3>Queen Mary University of London and the Royal Opera House</h3>
      <p class="meetup-date">10 May 2024</p>
      <p class="meetup-text">Talks on HRTF time-of-arrival estimation, perceptual tolerances in room acoustic rendering for VR and AR, choir source separation, ecological validity in spatial sound research and immersive audio challenges, followed by a backstage tour of the Royal Opera House.</p>
      <details>
        <summary>Programme</summary>
        <ul>
          <li class="meetup-sub">At Queen Mary, Mile End (15-minute talks plus 5 minutes for questions)</li>
          <li><strong>10:00–10:30</strong> Tea and coffee</li>
          <li><strong>10:30–10:40</strong> Participant introductions</li>
          <li><strong>10:40–11:00</strong> Chin-Yun Yu (Queen Mary University of London), <em>Time-of-arrival estimation and phase unwrapping of head-related transfer functions with integer linear programming</em></li>
          <li><strong>11:00–11:20</strong> Annika Neidhardt (University of Surrey), <em>Perceptual Tolerances in Room Acoustic Rendering for VR and AR</em></li>
          <li><strong>11:20–11:40</strong> Saurjya Sarkar (Queen Mary University of London), <em>Time-domain music source separation for choirs and ensembles</em></li>
          <li><strong>11:40–12:00</strong> Angela McArthur (UCL), <em>Ecological validity in spatial sound research – why?</em></li>
          <li><strong>12:00–12:20</strong> Lorenzo Picinali (Imperial College London), <em>Immersive Audio Challenges</em></li>
          <li><strong>12:20–13:00</strong> Lunch</li>
          <li class="meetup-sub">At the Royal Opera House</li>
          <li><strong>13:30–14:30</strong> Introduction and talk about the Royal Opera House, its broadcasts and the building</li>
          <li><strong>14:30–15:00</strong> Q&amp;A</li>
          <li><strong>15:00–16:00</strong> Backstage tour</li>
        </ul>
        <p class="meetup-credit">Organised by Aidan Hogg, with the other SIG coordinators.</p>
      </details>
      <details>
        <summary>Photos</summary>
        <div class="row meetup-photos">
          <div class="col-6">
            <img src="/assets/img/ROH_2024_control_room.jpg" alt="Royal Opera House staff showing a dummy head microphone in a control room" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/20240510_153036-scaled.jpg" alt="Attendees in the Royal Opera House orchestra pit" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/ROH_2024_auditorium.jpg" alt="The Royal Opera House auditorium seen from the orchestra pit" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/20240510_153828-scaled.jpg" alt="The Royal Opera House stage seen from the auditorium" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/20240510_154640-scaled.jpg" alt="Scenery and lighting rigs backstage at the Royal Opera House" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/20240510_154748-scaled.jpg" alt="The Royal Opera House stage from backstage" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/ROH_2024_paul_hamlyn_hall.jpg" alt="The Paul Hamlyn Hall at the Royal Opera House" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/20240510_160223-scaled.jpg" alt="Attendees in the Royal Opera House broadcast control room" class="img-fluid rounded" loading="lazy">
          </div>
          <div class="col-6">
            <img src="/assets/img/20240510_163854-scaled.jpg" alt="Mixing desk in the Royal Opera House broadcast suite" class="img-fluid rounded" loading="lazy">
          </div>
        </div>
        <p class="meetup-credit">Some photos by Chin-Yun Yu.</p>
      </details>
    </div>
  </div>
</div>
<div class="meetup">
  <div class="row">
    <div class="col-sm-5 meetup-image">
      <img src="/assets/img/SAIA_2023.png" alt="Group photo at Imperial College London, April 2023" class="img-fluid rounded z-depth-1" loading="lazy">
    </div>
    <div class="col-sm-7 meetup-body">
      <h3>Imperial College London and Sonos</h3>
      <p class="meetup-date">21 April 2023</p>
      <p class="meetup-text">Presentations from attendees, a tour of Imperial’s acoustics lab and a talk from the Sonos London team.</p>
      <details>
        <summary>Programme</summary>
        <ul>
          <li><strong>13:30–14:00</strong> Tea and coffee</li>
          <li><strong>14:00–14:15</strong> Participant introductions</li>
          <li><strong>14:15–15:30</strong> Presentations from attendees</li>
          <li><strong>15:30–16:00</strong> Tour of the Imperial acoustics lab</li>
          <li><strong>16:00–17:15</strong> Talk from the Sonos London team on their work and interests</li>
          <li><strong>17:15–17:30</strong> Discussion on taking the group’s activities forward</li>
        </ul>
        <p class="meetup-credit">Organised by Lorenzo Picinali and Aidan Hogg, with the other SIG coordinators.</p>
      </details>
      <details>
        <summary>Photos</summary>
        <div class="row meetup-photos">
          <div class="col-6">
            <img src="/assets/img/SAIA1-1024x768.png" alt="Attendees touring the Imperial College London acoustics lab" class="img-fluid rounded" loading="lazy">
          </div>
        </div>
      </details>
    </div>
  </div>
</div>
<div class="meetup">
  <div class="row">
    <div class="col-sm-5 meetup-image">
      <img src="/assets/img/l-acoustics_2022.jpeg" alt="Group photo at the L-Acoustics London showroom, June 2022" class="img-fluid rounded z-depth-1" loading="lazy">
    </div>
    <div class="col-sm-7 meetup-body">
      <h3>L-Acoustics Showroom, London</h3>
      <p class="meetup-date">20 June 2022</p>
      <p class="meetup-text">Our first meet-up: a listening session in the L-Acoustics Sound Space and its 18.1.12 loudspeaker system, with demos from the L-Acoustics team, a playback of pieces from the Student 3D Audio Production Competition in Ambisonics run by IEM Graz and the VDT, and a demo of creation tools.</p>
      <details>
        <summary>Programme</summary>
        <ul>
          <li><strong>16:20–17:00</strong> L-Acoustics demos</li>
          <li><strong>17:00–17:10</strong> Break</li>
          <li><strong>17:15–18:00</strong> 3D sound compositions: a selection of pieces from the Student 3D Audio Production Competition in Ambisonics, organised each year by the Institute of Electronic Music and Acoustics (IEM) in Graz with the German Association for Audio Professionals (VDT)</li>
          <li><strong>18:00–18:30</strong> Creation tools demo</li>
        </ul>
        <p class="meetup-credit">Organised by Rapolas Daugintis and Lorenzo Picinali, with the other SIG coordinators.</p>
      </details>
    </div>
  </div>
 
</div>
