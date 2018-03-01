---
layout: main
title: Projects
permalink: /projects/
---

<div class="card"><center>
  <img src="/images/build.gif">
</center><h1>Particle Offline Utility:</h1><a href="https://github.com/nrobinson2000/po-util/issues">
  <img src="https://img.shields.io/github/issues/nrobinson2000/po-util.svg">
</a>
  <a href="https://github.com/nrobinson2000/po-util/stargazers">
  <img src="https://img.shields.io/github/stars/nrobinson2000/po-util.svg">
</a>
  <a href="https://travis-ci.org/nrobinson2000/po-util">
  <img src="https://travis-ci.org/nrobinson2000/po-util.svg?branch=master" alt="Build Status">
</a>
  <a href="https://travis-ci.org/nrobinson2000/homebrew-po">
  <img src="https://travis-ci.org/nrobinson2000/homebrew-po.svg?branch=master">
</a><p><a href="https://github.com/nrobinson2000/po-util">Po-util</a>, short for Particle Offline Utility, is a tool I maintain for facilitating the ultimate local Particle development experience.</p><p>
    Po-util is my personal solution to local Particle development that uses the GCC for ARM Cortex processors toolchain to build your projects using the <a href="https://github.com/spark/firmware">Particle Firmware Source</a> directly on your computer.
    Po-util can be installed on macOS using Homebrew:
  </p><pre><code><strong class="shell">$</strong> bash <(curl -sL <a href="https://get.po-util.com">get.po-util.com</a>)</code>
</pre><p>Read more about <strong>po-util</strong> at <a href="https://po-util.com/">https://po-util.com/</a></p><p>Read <a href="https://particle.hackster.io/nrobinson2000/how-to-develop-particle-locally-using-po-util-e3227f?ref=channel&amp;ref_id=286_trending___&amp;offset=22">my article on Hackster about po-util.</a></p></div>

--------------------------------------------------------------------------------

<div class="card"><center>
  <img src="/images/demo.gif">
</center><h1>Particle Bash Completion:</h1><a href="https://travis-ci.org/nrobinson2000/particle-cli-completion">
  <img src="https://travis-ci.org/nrobinson2000/particle-cli-completion.svg?branch=master">
</a> <a href="https://github.com/nrobinson2000/particle-cli-completion">
  <img src="https://img.shields.io/badge/view%20on-GitHub-blue.svg">
</a><p>
    I created a bash completion script that accelerates and complements the <a href="https://www.particle.io/products/development-tools/particle-command-line-interface">Particle Command Line Interface</a>, providing command suggestions and completions when the tab key is pressed.
  </p><p>
    I additionally created an <a href="https://github.com/nrobinson2000/particle-cli-completion/blob/master/install">installation script for the completion</a> that helps users install the completion script on their computer:</p>
    <pre><code><strong class="shell">$</strong> bash &lt;(curl -sL <a href="https://git.io/vQWZD">https://git.io/vQWZD</a>)</code>
</pre></div>



--------------------------------------------------------------------------------



<div class="card">
  <center>
  <img src="/images/Particle-Pi.png">
</center>
  <h1>Setup guide for Particle on Raspberry Pi:</h1>
  <a href="https://particle.hackster.io/nrobinson2000/how-to-run-particle-on-raspberry-pi-headless-on-pi-zero-w-cd3ca2?ref=channel&amp;ref_id=286_trending___&amp;offset=5">
  <img src="https://img.shields.io/badge/view%20on-Hackster-blue.svg">
</a>
  <p>
    Recently I published a <a href="https://particle.hackster.io/nrobinson2000/how-to-run-particle-on-raspberry-pi-headless-on-pi-zero-w-cd3ca2?ref=channel&amp;ref_id=286_trending___&amp;offset=5">guide on Hackster</a> explaining how to use Raspberry Pi
    with the Particle Platform in order to access inputs and outputs and dynamicaly control processes on the Raspberry Pi itself. The setup is compatible with the new <a href="https://www.raspberrypi.org/blog/raspberry-pi-zero-w-joins-family/">Raspberry Pi Zero Wireless.</a>

    <br><br> If you already have a Raspberry Pi and a Particle account that is accepted into the Open Raspberry Pi Beta, you can get quickly get Particle running with these commands on your Pi:

    </p>
  <pre><code><strong class="shell">$</strong> sudo apt update &amp;&amp; sudo apt upgrade
<strong class="shell">$</strong> bash &lt;( curl -sL <a href="https://particle.io/install-pi">https://particle.io/install-pi</a> )</code>
</pre>
  <p>
</p>
</div>

--------------------------------------------------------------------------------



<div class="card"><center>
  <img src="/images/bitcoin.png">
</center><h1>Bitcoin Donation Page Generator:</h1><a href="https://github.com/nrobinson2000/donate-bitcoin/issues">
  <img src="https://img.shields.io/github/issues/nrobinson2000/donate-bitcoin.svg">
</a>
  <a href="https://github.com/nrobinson2000/donate-bitcoin/stargazers">
  <img src="https://img.shields.io/github/stars/nrobinson2000/donate-bitcoin.svg">
</a><p>I have created a simple HTML plugin that lets users easily create a page for them to accept Bitcoin donations. It has many features, including generating a unique scan-to-donate QR code and creating a click-to-donate link. It is highly configurable,
    as its variables can be set in a query in the URL. For a demo, click this button.
    <a href="http://nrobinson2000.github.io/donate-bitcoin/?amount=10&amp;currency=USD"><img src="https://img.shields.io/badge/donate-$10-orange.svg"></a></p><p>For more information, check out the repository on <a href="https://github.com/nrobinson2000/donate-bitcoin">GitHub</a>.</p><p>
</p><p>
</p></div>



--------------------------------------------------------------------------------
