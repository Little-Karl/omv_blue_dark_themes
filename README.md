# OMV Blue Dark Theme
Alternative Theme for OpenMediaVault (OMV NAS) Admin GUI

## Usage / Installation
Connect to the server via SSH and create a new <code>theme-custom.css</code>:
<br>
<pre>
<code>nano /var/www/openmediavault/css/theme-custom.css</code>
</pre>
or
<pre>
<code>cd /var/www/openmediavault/css</code>
<code>nano theme-custom.css</code>
</pre>
<br>
Paste code content of <code>theme-custom.css</code>. Set permissions of the file to:
<br>
<br>
<pre>
<code>openmediavault-webgui</code>
</pre>

#### Set owner
<pre>
<code>chown openmediavault-webgui:openmediavault-webgui theme-custom.css</code>
</pre>

#### Optional
Edit file **defaults.scss**. Adjust the <code>omv</code> default values at the end of the file:
<pre>
<code>
$omv-color-more-lighter: #b2c2cd;
$omv-color-lighter: #6897b6;
$omv-color-default: #1b5d88;
$omv-color-darker: #0b1625;
$omv-color-more-darker: #0b1625;
</code>
</pre>

##### The created Custom CSS currently works with OMV v5.
No guarantee can be given for older versions. Just try it out.
<br>
<br>
Have Fun ;-)
