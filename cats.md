---


---

<p><strong># REQUIRES</strong></p>
<ul>
<li>Node.js (LTS) : v18 and v20;</li>
<li>Package manager Node.js : Yarn, Npm ( &gt;= v6 );</li>
<li>PostgreSQL : &gt;= v11.</li>
</ul>
<p><strong># ENVORIMENT VARIABLES</strong></p>
<ul>
<li>Create .env file;</li>
<li>Replace the variables for .env.example;</li>
<li>Use the command <code>openssl rand -base64 32</code> to generate the variables: TRANSFER_TOKEN_SALT, ADMIN_JWT_SECRET, API_TOKEN_SALT, APP_KEYS and JWT_SECRET.<br>
* Recommendations : generate different strings for variables.</li>
</ul>
<p><strong># INITIALIZATION</strong></p>
<p>In your terminal</p>
<ul>
<li><code>cd cats-strapi-app</code>;</li>
<li><code>npm install or yarn install</code>;</li>
<li><code>npm run develop or yarn develop</code>.</li>
</ul>

