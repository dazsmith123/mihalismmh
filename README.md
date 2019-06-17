What's different in <strong>Mihalism-SE v1.0.0</strong> over <strong>Mihalism v5.0.3</strong> so far?

<ul>
	<li><strong>New feature:</strong> Added new user profile system with birthday selection, mood selection, and more.</li>
	<li><strong>New feature:</strong> Added new built-in cron job system will help your image host stay running smoothly, even when you're not around!</li>
	<li><strong>New feature:</strong> Added the ability to view and reply to emails sent through the contact form within Admin CP (requires mail server).</li>
	<li><strong>New feature:</strong> Added the ability to add new users from within admin panel.</li>
	<li><strong>New feature:</strong> Added new built-in captcha system, also the ability to enable google reCaptcha v2 (with your own api keys).</li>
	<li><strong>New feature:</strong> The new install script will guide you through the installation of Mihalism-SE step by step, it's as easy as 1-2-3!</li>
	<li><strong>New feature:</strong> Added new announcements page allowing you to keep your users up to date.</li>
	<li><strong>New feature:</strong> Added the ability to show your latest twitter tweets on homepage and announcements page.</li>
	<li><strong>New feature:</strong> Added 'Mihalism-SE Security Console' feature to admin panel which will advise you of potential security issues with your setup.</li>
	<li><strong>Updated:</strong> PHP 7 Support</li>
    <li><strong>Updated:</strong> The smarty templating will help your image host get better perfomance.</li>
	<li><strong>Updated:</strong> New website logging system to admin panel.</li>
	<li><strong>Updated:</strong> All known Windows 'file path bugs' should be fixed.*</li>
	<li><strong>Updated:</strong> Removed useless feature 'search engine logs' from admin panel.</li>
	<li><strong>Updated:</strong> Updated for more stable and user-friendly ajax enabled system information page.</li>
	<li><strong>Updated:</strong> Added ability (set by default) for public user images to show in the 'public gallery'.</li>
	<li><strong>Security:</strong> The Mihalism-SE database class is based on PDO, which will better help prevent SQL injection.</li>
	<li><strong>Security:</strong> Better protection against XSS injection.</li>
	<li><strong>Security:</strong> New powerful CSRF protection.</li>
	<li><strong>Security:</strong> Fixed bug where user can rate any value any image they want by editing the html value.</li>
    <li><strong>Security:</strong> Fixed bug where user can rate own images.</li>
	<li><strong>Security:</strong> Fixed bug where user can upload to any album they wish.</li>
	<li><strong>Security:</strong> Removed URL uploads features due critical security concern.</li>
	<li><strong>Other:</strong> Bug fixes, optimization, and enhancements.</li>
</ul>

*<strong>Please note:</strong> Windows will not be officially supported in Mihalism-SE, you will run Mihalism-SE on your Windows box at your own risk.

And much more to come, stay tuned for more updates :)

Notes:

Minimal System Requirements:
<ul>
	<li>VPS or Dedicated server (Shared hosting is not recommended or supported).</li>
	<li>Linux Operating System. Most distributions will work (Ubuntu >= 16.04 is recommended).</li>
	<li>Apache Web Server</li>
	<li>MySQL with PDO Support</li>
	<li>PHP 5.6.0 or above</li>
	<li>GD Library (Imagick 'ImageMagik' is more advanced and is recommended).</li>
	<li>PHP Session Support</li>
</ul>

Recommended System Requirements:
<ul>
	<li>VPS or Dedicated Server (Shared hosting is not recommended or supported).</li>
	<li>Linux Operating System: Ubuntu 16.04 or above distribution.</li>
	<li>Apache Web Server</li>
	<li>MySQL with PDO Support</li>
	<li>PHP 7.0, 7.1, or 7.2</li>
	<li>Imagick PHP Library</li>
	<li>PHP Session Support</li>
</ul>

-If there is enough demand after release of the fork, I will write an upgrade script for v5.0.x users. That means existing image hosts will be able to upgrade to Mihalism-SE with little effort. If you are interested in this, feel free to contact me to let me know.

-The estimated completion date of this fork will be sometime in middle of <strong>July 2019</strong>.

-You can contact me for any further details or updates @ daz[at]dazsmith.net.

Best wishes,
Daz
