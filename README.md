<h1>Quickstart for Installing and Using ownCloud</h1>

<h2>As an administrator, how do I install and configure an ownCloud server?</h2>

<p><strong>IMPORTANT:</strong> When the ownCloud prerequisites are fulfilled and all ownCloud files are installed, you can install and configure an ownCloud server by running the Installation wizard. </p>

<p>This involves three steps:</p>

<ol>
<li>Point your web browser to <strong>http://your-owncloud-domain</strong></li>
<li>Enter your desired administrator’s username and password</li>
<li>Click <strong>"Finish Setup"</strong> </li>
</ol>

<p><img src="https://doc.owncloud.com/server/10.8/admin_manual/_images/installation/install-wizard-a.jpg" alt="alt text" title="" /></p>

<p>You can now start using your new ownCloud server.</p>

<p><strong>NOTE:</strong> Click on hyperlinks below to view detailed information about Installation wizard:</p>

<ol>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/installation/installation_wizard.html#installation-configuration-options">Installation Configuration options</a></li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/installation/installation_wizard.html#database-setup-by-owncloud">Database Setup by ownCloud</a></li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/installation/installation_wizard.html#post-installation-steps">Post-Installation Steps</a></li>
</ol>

<h2>As an administrator, how do I add a user account?</h2>

<p>You can add a user account in User Configuration interface.</p>

<p>To add a user account:</p>

<ol>
<li>Enter the user's <strong>Login Name</strong> and <strong>E-mail</strong></li>
<li>Optionally, assign <strong>Group</strong> memberships</li>
<li>Click the <strong>"Create"</strong> button</li>
</ol>

<p><img src="https://doc.owncloud.com/server/10.8/admin_manual/_images/configuration/user/users-page-new-user.png" alt="alt text" title="" /></p>

<p><strong>NOTE:</strong> Login names may contain letters (a-z, A-Z), numbers (0-9), dashes (-), underscores (_), periods (.) and at signs (@).</p>

<h2>As an administrator, how do I connect to the ownCloud server using a desktop or mobile client?</h2>

<p>OpenID Connect which is an open standard for single sign-on, identity and access management helps to connect to the ownCloud server using a desktop or mobile client. It can be used for user authentication and client authorization against an External Identity Provider(IdP).</p>

<p><strong>IMPORTANT:</strong> ownCloud only supports one configured identity provider which is valid for all requests.</p>

<p><strong>NOTE:</strong> Please click on following hyperlinks for more details: </p>

<ul>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/configuration/user/oidc/oidc.html#prerequisites">Prerequisites</a></li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/configuration/user/oidc/oidc.html#set-up-service-discovery">Set Up Service Discovery</a> </li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/configuration/user/oidc/oidc.html#owncloud-desktop-and-mobile-clients">ownCloud Desktop and Mobile Clients</a> </li>
</ul>

<h2>As an administrator, how do I enable users to connect to the ownCloud server using the server's IP address and port 8080?</h2>

<p>The standard is to use [protocol]://[IP]:[port]. Example: http://127.0.0.1:8080.</p>

<p>You can install and configure <a href="https://letsencrypt.org/">Let's Encypt</a> SSL certificate which is the certificate authority for your ownCloud server. Certificates can be used by ownCloud to enable secure HTTPS connections using server's IP address and port.</p>

<p><strong>NOTE:</strong> Please click on following hyperlinks for more details:</p>

<ul>
<li><a href="https://doc.owncloud.com/server/admin_manual/installation/letsencrypt/using_letsencrypt.html#requirements-dependencies">Requirement and Dependencies</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/installation/letsencrypt/using_letsencrypt.html#install-lets-encrypts-certbot-client">Install Let's Encrypt Certbot Client</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/installation/letsencrypt/using_letsencrypt.html#register-your-email-address">Register your Email Address</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/installation/letsencrypt/using_letsencrypt.html#create-lets-encrypts-config-files">Create Let's Encrypt Configuration Files</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/installation/letsencrypt/using_letsencrypt.html#create-an-ssl-certificate">Create an SSL Certificate</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/installation/letsencrypt/using_letsencrypt.html#web-server-setup">Web Server Setup</a></li>
</ul>


