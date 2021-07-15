<h1>Quickstart for Installing and Using ownCloud</h1>

<h2>As an administrator, how do I install and configure an ownCloud server?</h2>

<p>When the ownCloud prerequisites are fulfilled and all ownCloud files are installed, you can install and configure an ownCloud server by running the Installation wizard. </p>

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

<p>OpenID Connect(OIDC) is an open standard for Single Sign-On(SSO), Identity and Access management which helps to connect to the ownCloud server using a desktop or mobile client. It can be used for user authentication and client authorization against an External Identity Provider(IdP).</p>

<p><strong>IMPORTANT:</strong> ownCloud only supports one configured identity provider which is valid for all requests.</p>

<p><strong>NOTE:</strong> Please click on following hyperlinks for more details:</p>

<ul>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/oidc/oidc.html#introduction">Introduction</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/oidc/oidc.html#supported-identity-providers">Supported Identity Providers</a></li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/configuration/user/oidc/oidc.html#prerequisites">Prerequisites</a></li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/configuration/user/oidc/oidc.html#set-up-service-discovery">Set Up Service Discovery</a> </li>
<li><a href="https://doc.owncloud.com/server/10.8/admin_manual/configuration/user/oidc/oidc.html#owncloud-desktop-and-mobile-clients">ownCloud Desktop and Mobile Clients</a> </li>
</ul>

<h2>As an administrator, how do I enable users to connect to the ownCloud server using the server's IP address and port 8080?</h2>

<p>Integrating Lightweight Directory Access Protocol(LDAP) application allows you to enable users to connect to the ownCloud server using the server's IP address and port 8080. </p>

<p>To configure :</p>

<ol>
<li>Install the <a href="https://marketplace.owncloud.com/apps/user_ldap">LDAP Integration application</a></li>
<li>Go to the Administration page to configure it</li>
</ol>

<p><strong>NOTE:</strong> LDAP configuration panel has four tabs:</p>

<ol>
<li>Server</li>
<li>Users</li>
<li>Login Attributes</li>
<li>Groups</li>
</ol>

<p><strong>IMPORTANT:</strong> You can enable users to connect to the ownCloud server by configuring settings in Server, Users and Login Attributes tabs.</p>

<h3>Server tab</h3>

<p>Correctly filling the Server tab's form is mandatory to access to other tabs. A green indicator light appears when the configuration is correct. Hover your cursor over the fields to see some pop-up tooltips.</p>

<p><img src="https://doc.owncloud.com/server/admin_manual/_images/apps/user_ldap/ldap-wizard/server-tab.png" alt="alt text" title="" /></p>

<h3>Users tab</h3>

<p>This interface is used to control which LDAP users are listed as ownCloud users on your ownCloud server. Use the Login Attributes tab in order to control which LDAP users can log in to your ownCloud server. If you prefer, bypass the form fields and enter a raw LDAP filter. </p>

<p><img src="https://doc.owncloud.com/server/admin_manual/_images/apps/user_ldap/ldap-wizard/users-tab.png" alt="alt text" title="" /></p>

<h3>Login Attributes tab</h3>

<p>The settings in the Login Attributes tab determine which LDAP users can log in to your ownCloud system. You may select multiple user details. If you prefer, bypass the form fields and enter a raw LDAP filter. </p>

<p><img src="https://doc.owncloud.com/server/admin_manual/_images/apps/user_ldap/ldap-wizard/login-attributes-tab.png" alt="alt text" title="" /></p>

<p><strong>NOTE:</strong> Please click on following hyperlinks for more details:</p>

<ul>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#introduction">Introduction</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#configuration">Configuration</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#server-tab">Server Tab</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#ldaps-configuration">LDAPS Configuration</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#user-filter">User Filter</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#login-filter">Login Filter</a></li>
<li><a href="https://doc.owncloud.com/server/admin_manual/configuration/user/user_auth_ldap.html#testing-the-configuration">Testing the Configuration</a></li>
</ul>



