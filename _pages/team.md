---
layout: page
title: Meet the Team
---

<style>
  html:not(.happy) .cta-streamlined-card:hover { background:#fff; color:#000; }
  html.happy .cta-streamlined-card:hover { background:#000; color:#fff; }

  .cta-wrap { position:relative; margin-bottom:2rem; }
  .cta-overlay {
    position:absolute; inset:0; z-index:2;
    display:block;
  }
  .cta-streamlined-card {
    position:relative; z-index:1;
    display:flex; align-items:center; justify-content:space-between;
    border:2px solid currentColor; border-radius:12px;
    padding:14px 10px 14px 20px;
    transition:background-color .3s ease, color .3s ease;
    text-decoration:none; color:inherit;
  }

  /* New member layout styles: floated circular photos with shape-outside so text wraps around the circle */
  .member { margin-bottom: 2em; }
  .member::after { content: ""; display: table; clear: both; }
  .member img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    display: block; /* required for shape-outside */
    -webkit-clip-path: circle(50% at 50% 50%);
    clip-path: circle(50% at 50% 50%);
  }
  .photo-left {
    float: left;
    margin-right: 20px;
    -webkit-shape-outside: circle(50% at 50% 50%);
    shape-outside: circle(50% at 50% 50%);
    shape-margin: 12px;
  }
  .photo-right {
    float: right;
    margin-left: 20px;
    -webkit-shape-outside: circle(50% at 50% 50%);
    shape-outside: circle(50% at 50% 50%);
    shape-margin: 12px;
  }
  
.member {
  display: flex;
  align-items: center;
  gap: 20px;
    margin-bottom: 2em;
}

.photo-left,
.photo-right {
  float: none;              /* disable float */
  shape-outside: none;      /* disable circular wrapping */
}

.photo-left {
  order: 0;
}

.photo-right {
  order: 1;
}

.member-text {
  flex: 1;
}

.member-text h3 {
  text-align: left;
}

.member img.photo-left + .member-text p {
  text-align: justify;
}

.member img.photo-right + .member-text p {
  text-align: justify;
}

  /* Responsive: stack on narrow screens */
  @media (max-width: 640px) {
    .photo-left, .photo-right { float: none; margin: 0 auto 1em; display:block; }
    .member img { margin: 0 auto; }
  }
</style>

<div class="cta-wrap">
  <a class="cta-overlay" href="/streamlined.html" aria-label="Open Streamlined"></a>

  <div class="cta-streamlined-card">
    <div style="text-align:left; flex:1;">
      <h3 style="margin:0 0 .25rem 0;">Streamlined</h3>
      <p style="margin:0; opacity:.85;">Our research group brings together scientists from many different backgrounds, including molecular biologists, human neuroscience researchers, behavioral specialists, computer scientists, and animal trainers. We do not work in isolated silos; instead, we organise around projects and tackle questions collaboratively. We work on different levels of analysis, but meet every week to share our work and results. This is both challenging – because each field has its own language, methods, and way of thinking – and an opportunity to build a shared vocabulary, learn each other’s logic, and develop truly multi‑perspective solutions. In today’s world, this kind of interdisciplinary approach is essential for doing innovative, productive science that leads to meaningful discoveries. We collaborate closely with clinicians because their feedback helps us pose research questions focused on real clinical needs. This collaboration accelerates the path from basic research discoveries to new diagnostic and therapeutic approaches. As a result, our findings can reach patients as quickly as possible.</p>
    </div>
  </div>
</div>

<!-- Team members: use .member with floated .photo-left or .photo-right to enable shape-outside -->

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Dani2.JPEG" alt="Dániel Hillier">
  <div class="member-text">
    <h3>Dániel Hillier, groupleader </h3>
    <p>As the head of the group in vision neuroscience, gene therapy, image processing, microscopy, and machine vision, I lead a multidisciplinary team working to reopen adult brain "windows of plasticity" through viral vector therapies, behavioral studies, and advanced models from mice to primates. What motivates me is the opportunity to contribute to sight restoration and clinical therapies, striving for meaningful progress in helping those with severe neurological and psychiatric conditions.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Doma.JPG" alt="Domonkos Horváth">
  <div class="member-text">
    <h3>Domonkos Horváth, postdoc </h3>
    <p>As a postdoc in the lab, my research centers on chronic imaging experiments in large-brained animals, primarily under anesthesia. In our lab, I plan, organize, and conduct these experiments collaboratively with our team, and advancing our understanding of brain function through precise and systematic application of chronic imaging approaches through a good team effort is what matters the most to me. Outside the lab, I support scouting with my volunteer work and I am keen on hiking with my family and friends.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Trixi.jpeg" alt="Beatrix Kovács">
  <div class="member-text">
    <h3>Beatrix Kovács, PhD student </h3>
    <p>In the lab, I focus on molecular biology and cell-based work. What matters most to me is clarity - in experimental design, documentation, and everyday lab work - because good science needs structure, not chaos. Outside the lab, I recharge through art, especially theater, concerts, and exhibitions.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Klau.jpeg" alt="Klaudia Csikós">
  <div class="member-text">
    <h3>Klaudia Csikós, PhD student </h3>
    <p>My work involves experimental design, implant and surgical preparation, and multimodal data acquisition and analysis to study how the brain processes visual information.
I value following my intuition, exploring the scientific literature, and finding creative ways to solve complex neuroscience questions.
Outside the lab, I find balance in painting, dancing, and spending time with friends.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Abel.jpg" alt="Ábel Petik">
  <div class="member-text">
    <h3>Ábel Petik, PhD student </h3>
    <p>I'm the main developer and data analyst of the functional brain imaging team. I take pride in the well thought out nature of the software we create. In my free time I cherish dancing and making music.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/" alt="Fanni Somogyi">
  <div class="member-text">
    <h3>Fanni Somogyi, PhD student </h3>
    <p>I am working with rodent and large animal models, combining surgical techniques, AAV-based delivery, functional imaging and tissue analysis. I am motivated by designing complex experiments that require careful planning and coordination, as this allows us to address meaningful scientific questions. Outside the lab, I am always up for a good conversation over coffee or a board game night with my husband and friends.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Beni.jpg" alt="Bendegúz Fekete">
  <div class="member-text">
    <h3>Bendegúz Fekete, MSc student </h3>
    <p>I work on our human EEG project, investigating brain alterations associated with amblyopia using a range of statistical methods. My main research interest is how perception works, with a particular focus on predictive coding.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Kinga.JPEG" alt="Sarolt Kinga Gintner">
  <div class="member-text">
    <h3>Sarolt Kinga Gintner MSc </h3>
    <p>In the group, I manage the work of the Animal House team, am responsible for the care and welfare of the animals and besides this, I research the visual aspects of higher-order species behavior. I'm particularly interested in decoding subtle animal signals, automating their measurement, and enhancing human-animal interactions to benefit both sides. Outside the lab, I teach experiential science, ride horses regularly, and apply my precision and creativity in a community leadership role.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Barna2.JPEG" alt="Barna Kovács">
  <div class="member-text">
    <h3>Barna Kovács, MSc student </h3>
    <p>I mainly work on the development side, so my strengths are in programming areas like data analysis and computational modelling. I enjoy spending my free time in nature, especially when it snows a little, and by playing board games.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/MPetra.jpeg" alt="Petra Molnár">
  <div class="member-text">
    <h3>Petra Molnár, MSc student </h3>
    <p>I work in the laboratory with AAV vectors and neutralizing antibody (NAb) testing. What I find important is continuous protocol improvement and methodological precision, I take pride in analyzing each step to make our processes more efficient and reliable, learning and refining our approaches every day. Outside the lab, I'm passionate about staying active through boxing and horse riding, exploring different cultures through travel, and expressing myself through creative hobbies.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Andris.jpg" alt="András Adolf">
  <div class="member-text">
    <h3>András Adolf, PhD student </h3>
    <p>I work in the behavior team, where I develop and maintain the experiment leader application used to run behavioral experiments.
I find it particularly important to write clear, reliable Python code that supports reproducible experiments and smooth collaboration within the lab.
Outside the lab, I enjoy running, playing the guitar, and spending time with friends over board games.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/K.Petra2.jpeg" alt="Petra Kornidesz">
  <div class="member-text">
    <h3>Petra Kornidesz, MSc student </h3>
    <p>I'm part of the behavioral team.
 What matters most to me in my work is creativity and precision, especially in how questions are framed and studied.
Outside the lab, I am passionate about sports, as it helps me recharge, and stay balanced.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Fanni.jpg" alt="Fanni Soós">
  <div class="member-text">
    <h3>Fanni Soós, BSC </h3>
    <p>I work as an assistant in the anatomy lab, where I support daily activities and pay close attention to precision and detail. I am proud of maintaining a clean, organized, and cosy lab environment, as I believe it contributes to better learning and work conditions. Outside the lab, I enjoy spending time reading and have a special fondness for cats.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Virag.JPG" alt="Virág György">
  <div class="member-text">
    <h3>Virág György, MSc </h3>
    <p>I work in the anatomy laboratory, where I focus on tissue sample processing, histological preparation, and experimental data analysis. I am continuously developing myself and learning new techniques, including rodent experimental methods. Beyond the lab, dancing plays an important role in my life - particularly folk dance, belly dance and West Coast Swing.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/B.Luca.jpg" alt="Luca Benedek">
  <div class="member-text">
    <h3>Luca Benedek, MSc student </h3>
    <p>I work as an animal house assistant in the laboratory. I find it important to maintain the animals’ well-being and support the researchers’ work effectively. Outside the lab, I love folk music and I am learning to play the zither and viola.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Hanna.jpg" alt="Hanna Orvos-Nagy">
  <div class="member-text">
    <h3>Hanna Orvos-Nagy, MSC student</h3>
    <p>My role is to assist the research group by taking care of the animals in the Animal House and the mice enclosure, monitoring their health, administering medication, and providing them with a comfortable and safe environment. In my spare time I enjoy creative activities, such as drawing, sewing and crafting, and I really love playing board games with my friends, sometimes for hours on end.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Zsombi.JPEG" alt="Zsombor Fülei">
  <div class="member-text">
    <h3>Zsombor Fülei, MSc student</h3>
    <p>In the research group I am an Animal House assistant, and my main responsibilities are daily cleanings and measuring out medications. Currently I'm a Master's student in Biology. Outside the lab my research focuses on the population genetics of ancient camels from the Pannonia region, I'm also interested in history, social sciences, the Serbian language and board games.</p>
  </div>
</div>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Gabi.jpg" alt="Gabriella Trieb">
  <div class="member-text">
    <h3>Gabriella Trieb MSc </h3>
    <p>I work as a research assistant on human EEG experiments. I enjoy working with people and helping participants feel informed and comfortable throughout the studies. In every season, I recharge through movement and sports in nature and have a strong interest in group dynamics and self-awareness.</p>
  </div>
</div>

<div class="member">
  <img class="photo-right" src="/assets/images/member_photos/Gabor.JPEG" alt="Gábor Ábrahám">
  <div class="member-text">
    <h3>Gábor Ábrahám, MSc student </h3>
    <p>Currently, I do microscopic image processing and cell segmentation in the lab. I find challenging myself important and like coming up with creative solutions to problems. Outside the lab, I am passionate about music, cooking and sports among a lot of other things.</p>
  </div>
</div>

<p>We are looking for more open-minded, passionate, and dedicated members to join our laboratory group. View our open positions <a href="https://drive.google.com/drive/u/0/folders/1wsbbJSXaonZvQbH3t1NIIn3Ize1NDEo6" target="_blank">here!</a></p>   

<h1> Alumni </h1>

<div class="member">
  <img class="photo-left" src="/assets/images/member_photos/Mariela.JPG" alt="Mariela Talavera Munoz">
  <div class="member-text">
    <h3>Mariela Talavera Munoz</h3>
    <p>I am Mariela Talavera, bacherlor student of biomedical engineering in Universidad Autónoma de Madrid. I am interested in medical imaging and prothesis design. I like playing piano and doing sports.</p>
  </div>
</div>

