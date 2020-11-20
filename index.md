## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/nhu313/test_githubpage/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
<div class="squatchembed"></div>

<script>
!function(a,b){a("squatch","https://fast.ssqt.io/squatch-js@2",b)}(function(a,b,c){var d,e,f;c["_"+a]={},c[a]={},c[a].ready=function(b){c["_" + a].ready =  c["_" + a].ready || [];c["_" + a].ready.push(b);},e=document.createElement("script"),e.async=1,e.src=b,f=document.getElementsByTagName("script")[0],f.parentNode.insertBefore(e,f)},this);
  
  // when squatch.js is ready to use
window.squatch.ready(function(){

  //place squatch.js functionality here

});

window.squatch.ready(function(){

squatch.init({
    tenantAlias: 'test_abzxg88g30tn2'
  });

  //object containing the init parameters for squatch.js
  var initObj = {

    //the object for the user you want to upsert
    user: {                               
      id: 'abc_123',                      
      accountId: 'abc_123',       
      email: 'john@example.com',                
      firstName: 'John',       
      lastName: 'Doe',
      locale: 'en_US'
    },
        jwt: 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjp7ImlkIjoiYWJjXzEyMyIsImFjY291bnRJZCI6ImFiY18xMjMiLCJlbWFpbCI6ImpvaG5AZXhhbXBsZS5jb20iLCJmaXJzdE5hbWUiOiJKb2huIiwibGFzdE5hbWUiOiJEb2UiLCJsb2NhbGUiOiJlbl9VUyJ9fQ.QfAsCpl91dbfT7M9mhWw9XIHgvyneRlCSD6dxomT-i4'
  };

  squatch.api().upsertUser(initObj).then(function(response) {
    user = response.user;
  }).catch(function(error){
    console.log(error);
  })

});
</script>
