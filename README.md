# EasyScurity
this is a scurity page for websites writen in pure javascript

# Instlation
1. make a clone
2. change the login and password in the list to your choice
3. link to it in your html
  <script src="/EasyScurity/main/secure.js"></script>
javascript:alert("you must type something and clicking cancel wont work"); let user=prompt("Username:"); let pass=prompt("Password:"); if (user===null || pass===null || user==="" || pass==="") { window.location.reload(); } //put the cotrrect user name in the username here //put the correct password in password here const correct= ["Username Here_Password Here"]; const user_pass = user+"_"+pass; if (correct.includes(user_pass)) { alert('Correct'); title.innerHTML="Loged In"; } else { alert('incorrect'); window.open('https://www.youtube.com/watch?v=xvFZjo5PgG0','_self'); }"<p>this is example text</p>"
