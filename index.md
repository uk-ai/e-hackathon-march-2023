---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<head>
<link rel="stylesheet" href="css/style.css">
<script src="js/functions.js"></script>
</head>

<!-- Tab links -->
<div class="tab">
  <button class="tablinks active" onclick="open_tab(event, 'description')">Description</button>
  <button class="tablinks" onclick="open_tab(event, 'location')">Location</button>
  <button class="tablinks" onclick="open_tab(event, 'schedule')">Schedule</button>
  <button class="tablinks" onclick="open_tab(event, 'material')">Material</button>
  <button class="tablinks" onclick="open_tab(event, 'participants'); load_file('participants/participants.csv','participants_table'">Participants</button>
</div>

<!-- Tab content -->
<div id="description" class="tabcontent" style="display: block;">
  <p>One of the key aspects to advance the Artificial Intelligence field is to build communities around ML and its applications. As a step towards this goal, we are holding the first Turing AI Fellows Community Hackathon, which will enable ML and domain experts to share their knowledge and start building research collaborations.</p>
  <p><strong><a href="https://forms.gle/UcR9fwZKjpamUAbD8" target="_blank">Registration is open here!</a></strong></p>
</div>

<div id="location" class="tabcontent">
  <p>Intel Lab</p>
  <p>William Gates Building</p>
  <p>15 JJ Thomson Ave, Cambridge, CB3 0FD</p>
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d576.8918776185558!2d0.09151032340100916!3d52.21099751785525!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47d8774a3f6e55cd%3A0xabf8227343e684c7!2sComputer%20Laboratory!5e0!3m2!1sen!2suk!4v1676307904600!5m2!1sen!2suk" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

<div id="schedule" class="tabcontent">
  <p>TBD...</p>
</div>

<div id="material" class="tabcontent">
  <p>TBD...</p>
</div>

<div id="participants" class="tabcontent">
  <div id="participants_table"></div>
</div>
