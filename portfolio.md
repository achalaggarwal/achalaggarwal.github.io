---
Title: Projects
layout: page
permalink: /projects/
---

A few of my recent projects...

<div id="portfoliotop"></div>
<div id="portfolio">
  <div class="portfolio-item">
    <a href="https://itunes.apple.com/us/app/opentable-for-ipad/id375864276?mt=8" rel="tooltip" title="April 2010 - Oct 2010<br /><br />This was a port of the original Opentable iPhone app to the iPad. With a completely custom UI, this brought the power of restaurant reservation to iPad. I worked on multiple release cycles of this app."><img src="https://dl.dropbox.com/s/julzvn6ujgjp8ia/opentable-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/t5h0y4bzhicxq0t/opentable.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/julzvn6ujgjp8ia/opentable-grey.png?dl=1'" /></a>
    <span class="name">Opentable for iPad</span>
  </div>
  <div class="portfolio-item">
    <a href="http://itunes.apple.com/us/app/disney-muppet-mail/id482268510?mt=8" rel="tooltip" title="Unfortunately, Disney has stopped selling the app on the Apple App Store as they have stopped promotion for the Muppets brand.<br /><br />May 2011 - Oct 2011<br /><br />The official iPad app to accompany the Disney Muppets movie released in November 2011. The app can be used to send customized greeting cards to your friends and family. I was the lead iOS developer on the project working alongside just one other team member."><img src="https://dl.dropbox.com/s/egexwwlrcjhqr2b/disney-muppets-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/wh47ql3749ahzi4/disney-muppets.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/egexwwlrcjhqr2b/disney-muppets-grey.png?dl=1'" /></a>
    <span class="name">Disney Muppet Mail</span>
  </div>
  <div class="portfolio-item">
    <a href="http://kinesis.io" rel="tooltip" title="A native development framework that allows you to make native gesture based applications with HTML, CSS and JavaScript."><img src="https://dl.dropbox.com/s/5kwijjzi7kyzf99/kinesis-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/sgfwmiy3s23a0dt/kinesis.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/5kwijjzi7kyzf99/kinesis-grey.png?dl=1'" /></a>
    <span class="name">Kinesis.io</span>
  </div>
  <div class="portfolio-item">
    <a href="http://getchute.com" rel="tooltip" title="June 2011 - Nov 2011<br /><br />Developed the drop-in Chute iOS SDK along with a few UI components, being used by hundreds of iOS developers right now. <br /><br />Launched in March, YCombinator (http://ycombinator.com) 2012 Alumni, Chute is a company which helps apps and sites capture, manage and display media files."><img src="https://dl.dropbox.com/s/zb9igu2cxwhk5nx/chute-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/7cmf59bz1wokfwk/chute.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/zb9igu2cxwhk5nx/chute-grey.png?dl=1'" /></a>
    <span class="name">Chute iOS SDK</span>
  </div>
  <div class="portfolio-item">
    <a href="http://www.iuktax.com" rel="tooltip" title="Jan 2010 - Feb 2010<br /><br />An app for the UK Tax payer, designed to calculate an individuals personal income taxes and National Insurance contributions. Also featured in The Guardian - http://www.guardian.co.uk/money/2010/oct/08/consumer-app-uk-taxwizard. "><img src="https://dl.dropbox.com/s/5j5gmig1nvbgh59/uktaxwizard-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/tkkn1ird7eaa3bu/uktaxwizard.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/5j5gmig1nvbgh59/uktaxwizard-grey.png?dl=1'" /></a>
    <span class="name">UK Tax Wizard 2010</span>
  </div>
  <div class="portfolio-item">
    <a href="http://tablime.com" rel="tooltip" title="Jan 2011 - March 2011<br /><br />Tablime is a product developed by iGate Corp. iGate Corp was a pioneer in developing one of the very first SaaS digital signage solutions back in 2000. iGate Corp is pioneering again with one of the very first tablet-based digital signage systems in the world. I developed the iPad app which enables the digital signage"><img src="https://dl.dropbox.com/s/140rhoutfe8d6ww/tablime-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/zgat3o3payxoxxw/tablime.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/140rhoutfe8d6ww/tablime-grey.png?dl=1'" /></a>
    <span class="name">Tablime for iPad</span>
  </div>
  <div class="portfolio-item">
    <a href="https://itunes.apple.com/us/app/univita-living-care-circles/id439053195?mt=8" rel="tooltip" title="July 2010 - Nov 2010<br /><br />Univita Living is designed to help you find, coordinate and manage the necessary resources to meet you or your loved one's independence needs. Worked on the initial design and release of the iPhone application."><img src="https://dl.dropbox.com/s/lghjbwkv4l0a1mu/univita-grey.png?dl=1" onmouseover="this.src='https://dl.dropbox.com/s/b0fcqtmv6bt7w44/univita.png?dl=1'" onmouseout="this.src='https://dl.dropbox.com/s/lghjbwkv4l0a1mu/univita-grey.png?dl=1'" /></a>
    <span class="name">Univita Living Care Circles iOS</span>
  </div>
</div>

<div id="portfoliobottom"></div>

<script type="text/javascript" src="http://code.jquery.com/jquery-latest.js"></script>
<script type="text/javascript">
$(document).ready(function() {

  //Select all anchor tag with rel set to tooltip
  $('a[rel=tooltip]').mouseover(function(e) {

      //Grab the title attribute's value and assign it to a variable
      var tip = $(this).attr('title');

      //Remove the title attribute's to avoid the native tooltip from the browser
      $(this).attr('title','');

      //Append the tooltip template and its value
      $(this).append('<div id="tooltip"><div class="tipHeader"></div><div class="tipBody">' + tip + '</div><div class="tipFooter"></div></div>');

      //Set the X and Y axis of the tooltip
      $('#tooltip').css('top', e.pageY + 10 );
      $('#tooltip').css('left', e.pageX + 20 );

      //Show the tooltip with faceIn effect
      $('#tooltip').fadeIn('500');
      $('#tooltip').fadeTo('10',0.8);

  }).mousemove(function(e) {

      //Keep changing the X and Y axis for the tooltip, thus, the tooltip move along with the mouse
      $('#tooltip').css('top', e.pageY + 10 );
      $('#tooltip').css('left', e.pageX + 20 );

  }).mouseout(function() {

      //Put back the title attribute's value
      $(this).attr('title',$('.tipBody').html());

      //Remove the appended tooltip template
      $(this).children('div#tooltip').remove();

  });

});
</script>
