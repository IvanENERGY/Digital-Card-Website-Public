<h1>&#9888; To protect interest of the client company, source code for this project would NOT be disclosed to public. </h1>
<h1>Project Introduction - Digital Business Card Website</h1>

![pj_bcard](https://github.com/user-attachments/assets/55b4c2fc-e9fb-4ca1-afce-d4f58db8f378)
<p>
Digital Business Card Website is a fully functional full-stack webpage designed for NFC Workshop Limited. It is built using the MERN stack:
</p>
<table>
<tbody>
  <tr>
    <th>Frontend</th>
    <td> ReactJS</td>
  </tr>
  <tr>
    <th rowspan="2">Backend</th>
    <td> NodeJS & Express JS</td>
  </tr>
  <tr>
    <td> MongoDB</td>
  </tr>
</tbody>
</table>
<p>It is deployed on the Internet using Render.com</p>
<p>The application supports the following functionalities:</p>
<ul>
<li>Register Account (with email verification for account activation)</li>
<li>Login/Logout</li>
<li>Forget Password Function with reset password token sent to user email</li>
<li>Contact Us which allow users to send email to site owner</li>
<li>&#65039;<strong>Business Card Generation </strong>: User enter personal data like name, phone number, address, websites, notes. The website would make use of these data to generate a Vcard, such that everyone on the web can have access to it and save it to phone's contact book </li>

</ul>

<p>&#11088;&#9989;<i>The application is user-friendly for both desktop and mobile devices</i></p>
<p>&#11088;&#128274;<i>Password, Password Reset Token, Account Activation Token are all protected inside database with Hashing + Salt</i></p>
<p>&#11088;&#128100; <i>Common practices like JSON web token (JWT) & Passport JS are used for authentication purpose</i></p>
<p>&#11088;	&#9202;<i>Password Reset Token, Account Activation Token would be automatically expired within 10 minutes once generated</i></p>
<p>&#11088;<i>Only activated account can login and access to "Generate Business Card" function</i></p>
<p>&#11088;	&#128465;<i>User Account which are not activated within 10 minutes would be automatically deleted</i></p>
<h1>Project Demo (YouTube)</h1>
<hr>

<h1>&#128247;Screenshots [ Top: Mobile , Bottom: Desktop]</h1>
<hr>
<h2>&#128311;Home Page (for Not logged in)</h2>
<h3><strong>MOBILE</strong></h3>

![homepage_nlogged_m](https://github.com/user-attachments/assets/6eaa4d6a-0c64-4fb2-ad51-4c89f8508c65)
<h3><strong>DESKTOP</strong></h3>
<img width="1916" alt="homepage_nlogged_d" src="https://github.com/user-attachments/assets/24014aa7-ad5f-4838-9e1b-13bd87569aa6">

<h2>&#128311;Home Page (for logged in)</h2>
<h3><strong>MOBILE</strong></h3>

![homepage_logged_m](https://github.com/user-attachments/assets/82549933-bfea-4ef9-98ab-7531ad4ec00c)
<h3><strong>DESKTOP</strong></h3>
<img width="1916" alt="homepage_logged_d" src="https://github.com/user-attachments/assets/81dbb5d1-7a67-4cfc-a13f-bad91fb25e0a">


<h2>&#128311;Login Page </h2>
<h3><strong>MOBILE</strong></h3>

![loginpage_m](https://github.com/user-attachments/assets/8f806281-4423-416b-83d5-94ca4987a8eb)
<h3><strong>DESKTOP</strong></h3>
<img width="1917" alt="loginpage_d" src="https://github.com/user-attachments/assets/5b1b128f-3d47-43a6-8393-b46c83b59009">
<h2>&#128311;Register Page </h2>
<h3><strong>MOBILE</strong></h3>

![regpage_m](https://github.com/user-attachments/assets/fc6b6de5-668a-4daf-8788-d5704fd3c0fb)
<h3><strong>DESKTOP</strong></h3>
<img width="1913" alt="regpage_d" src="https://github.com/user-attachments/assets/a16c1177-140d-4496-8cbf-f135c48bc3cc">
<h2>&#128311;Activation Email </h2>
<img width="1710" alt="act_email" src="https://github.com/user-attachments/assets/7bedcbc0-ad68-415d-bd42-f6562565d79a">
<h2>&#128311;Activation Page (by clicking link on activation email)</h2>
  <p>Success Activation</p>
<h3><strong>MOBILE</strong></h3>

  ![act_token_success_m](https://github.com/user-attachments/assets/c204a7ee-12c8-4a55-be3b-23243a6ffc72)
  <h3><strong>DESKTOP</strong></h3>
  <img width="1916" alt="act_token_success_d" src="https://github.com/user-attachments/assets/55eec18e-e7fb-4315-8187-0835938608ab">
  <p>Activation token expired</p>
<h3><strong>MOBILE</strong></h3>

  ![act_token_expire_m](https://github.com/user-attachments/assets/00c1ed12-484b-4b0e-b702-4844817b3cc8)
  <h3><strong>DESKTOP</strong></h3>
  <img width="1918" alt="act_token_expire_d" src="https://github.com/user-attachments/assets/d5b8e188-147c-4c0b-8994-f0ff1b3a9036">
<h2>&#128311;Forget Password Page</h2>
<h3><strong>MOBILE</strong></h3>

![forget_m](https://github.com/user-attachments/assets/b6013a14-1067-47ef-9f34-16b490f9289b)
<h3><strong>DESKTOP</strong></h3>

<img width="1919" alt="forget_d" src="https://github.com/user-attachments/assets/f5118493-f0b4-48a4-b6bb-0710ed99c490">

<h2>&#128311;Reset Password Email</h2>
<img width="1711" alt="reset_email" src="https://github.com/user-attachments/assets/0a5dcbea-befc-4ba7-8a36-1019c00b876e">
<h2>&#128311;Reset Password Page  (by clicking link on reset password email)</h2>
<p>Original</p>
<h3><strong>MOBILE</strong></h3>

  ![reset_page_m](https://github.com/user-attachments/assets/210b8a3c-795b-41cb-ad47-66549d215f11)
<h3><strong>DESKTOP</strong></h3>

  <img width="1918" alt="reset_page_d" src="https://github.com/user-attachments/assets/cc4e578c-c748-446e-8e32-90a8a55fc370">
  <p>Success Reset</p>
<h3><strong>MOBILE</strong></h3>

  ![reset_token_success_m](https://github.com/user-attachments/assets/4bc0332d-1971-4567-9ece-e0ec318a3c2f)
  <h3><strong>DESKTOP</strong></h3>
<img width="1913" alt="reset_token_success_d" src="https://github.com/user-attachments/assets/2c947711-1319-4149-ab98-3d1a7790435c">

  <p>Reset password token expired</p>
<h3><strong>MOBILE</strong></h3>

  ![reset_token_expire_m](https://github.com/user-attachments/assets/ac36ac51-bcde-48e2-a6d7-4219c9151900)
  <h3><strong>DESKTOP</strong></h3>
  <img width="1918" alt="reset_token_expire_d" src="https://github.com/user-attachments/assets/6ad03ae4-6175-478d-9d13-00be2e82c65d">
<h2>&#128311;Contact Us Page</h2>
<h3><strong>MOBILE</strong></h3>

![contact_m](https://github.com/user-attachments/assets/ac0fc5a0-ef4a-4a6c-83aa-b07517612501)
<h3><strong>DESKTOP</strong></h3>
<img width="1910" alt="contact_d" src="https://github.com/user-attachments/assets/f17140c4-b7bc-413e-9f55-2ccd6fc440d4">
<h2>&#128311;Contact Us Email (for client company)</h2>

![contact_email](https://github.com/user-attachments/assets/96821bf9-aaf8-4cee-9fc6-c884f7be863f)
<h2>&#128311;Change Password Page (for logged in user)</h2>
<h3><strong>MOBILE</strong></h3>

![changepw_m](https://github.com/user-attachments/assets/9feed0d0-48b4-402f-b826-dacb3d6ba933)
<h3><strong>DESKTOP</strong></h3>
<img width="1916" alt="changepw_d" src="https://github.com/user-attachments/assets/7a85eda7-67a6-4caf-899d-001a1a7f3a95">
<h2>&#128311;Business Card Generation - Edit Profile Page (for logged in user)</h2>
<h3><strong>MOBILE</strong></h3>

![editprofile_m](https://github.com/user-attachments/assets/d984a034-c8bf-47e1-9c5f-b303394b9062)
<h3><strong>DESKTOP</strong></h3>
<img width="1901" alt="editprofile1_d" src="https://github.com/user-attachments/assets/bed7ac7f-05cf-4a72-97ce-3421a5bd79f0">
<img width="1889" alt="editprofile2_d" src="https://github.com/user-attachments/assets/55befad3-f187-47c7-8856-93a3a7bb93d3">

<h2>&#128311;User Card Page (visible for everyone)</h2>
<h3><strong>MOBILE</strong></h3>

![card_m](https://github.com/user-attachments/assets/7607bfc6-c4df-4337-ad1e-013a4f01947e)
<h3><strong>DESKTOP</strong></h3>
<img width="1903" alt="card1_d" src="https://github.com/user-attachments/assets/90f27d90-5c92-4954-be50-71a80c02d63e">
<img width="1900" alt="card2_d" src="https://github.com/user-attachments/assets/dbdc3c0c-85a9-41aa-9ab1-3fc364f2c744">
<img width="1902" alt="card3_d_updated" src="https://github.com/user-attachments/assets/1307eb63-a2d7-4716-8cf2-6dbe6de664d1">
<br>
<h2>&#128311;Download UserCard</h2>
<h3><strong>MOBILE</strong></h3>

![downloadcard_m](https://github.com/user-attachments/assets/efc59b88-15d7-4a19-8aef-fffc022b2bb7)
<br>
<h3><strong>DESKTOP</strong></h3>
<img width="897" alt="downloadcard_d" src="https://github.com/user-attachments/assets/19f0f08a-739e-4105-959a-d11b5db299f6">

<hr>
<h1>&#128221;Devlopement Notes</h1>
<h2>**SETUP INDEX(UNIQUE &TTL) for Mongodb  document:</h2>
<h2>How to set up TTL for record?</h2>
<ol>
<li>include expireAt schema in mongoose schema</li>
<pre>
     expireAt: {
            type: Date,
                 
        }
</pre>
<li>Set this field whenever the object is created</li>
<pre>
ActivationToken.create({
                    tokenHash:tokenHashed,
                    userId:user._id,
                    expireAt:Date.now()+10*60*1000
                })
</pre>

<li>Set TTL index using mongo Compass</li>
<p> Fieldname:expireAt;type: Type - 1 ; TTL: 0 seconds</p>
<p>The document would be expired in 0 second after the date indicated in expiredAt</p>
<li><i>We can also unset the field when needed </i></li>
<pre>
   return User.findByIdAndUpdate( userId,{$set: {isActivated: true},$unset : {expireAt:null}}).exec()
</pre>
</ol>
<h2>//index for ttl in 3 tables </h2>
<p>screenshot1.png</p>
<p>activationtokens(expireat,0)</p>
<img width="1051" alt="screenshot1" src="https://github.com/user-attachments/assets/cb6fd8ec-2142-4f13-916b-8bdb268b3f9a">
<p>screenshot2.png</p>
<p>resettokens(expireat,0),</p>
<img width="1051" alt="screenshot2" src="https://github.com/user-attachments/assets/fa543d72-412b-4f4a-a1c7-509b6c4ffb43">
<p>screenshot3.png</p>
<p>users (expireat,0),</p>
<img width="1045" alt="screenshot3" src="https://github.com/user-attachments/assets/0bbdff27-5947-4b42-b659-bc24327996ae">
