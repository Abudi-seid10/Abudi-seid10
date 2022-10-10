<h1 align="center"> 👋 </h1>
<div align="center">
  <img src="https://github.com/Ileriayo/ileriayo/blob/master/images/header.gif" alt="header"/>
</div>
<p align="center"> (Open for Hiring)</p>

<h2 align="center"> 👨‍💻 Whoami</h2>
<p align="center">
  <samp>A highly resourceful Graphic Designer and Full Stack Django Developer. I have made Bolgs and Portfolio Websites for clients as a freelancer.
  </samp>
  <br> <br>
  <img src="https://komarev.com/ghpvc/?username=Abudi-seid10" alt="https://github.com/Abudi-seid10" />
</p>

<hr>

<h2 align="center"> 🔭 Tools of Trade</h2>
<p align="center">
  <img src="https://img.shields.io/badge/Python%20-%2343853D.svg?&style=for-the-badge&logo=python&logoColor=white" />&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Django%20-%2300D9FF.svg?&style=for-the-badge&logo=django&logoColor=white" />&nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Bootstrap%20-%231572B6.svg?&style=for-the-badge&logo=Bootstrap&logoColor=white" />&nbsp;&nbsp;
</p>
<p align="center"> Python, Git, Github, Bitbucket, Bootstrap, Django, Jinja2.</p>

<hr>
<!-- 
<h2 align="center">💬 My Blog Articles</h2>

<p align="center" align='right'>
  <a target="_blank"href="https://dev.to/ileriayo"><img src="https://img.shields.io/badge/dev.to-%2312100E.svg?&style=for-the-badge&logo=dev.to&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;
  <a target="_blank"href="https://medium.com/@ileriayoadebiyi"><img src="https://img.shields.io/badge/Medium%20-%231572B6.svg?&style=for-the-badge&logo=medium&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;
</p>
 -->
 <img align="left" src="https://github-readme-stats.vercel.app/api?username=Abudi-seid10&show_icons=true&count_private=true&theme=gruvbox" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abudi-seid10&layout=compact&count_private=true&theme=gruvbox" />

<hr>

<h2  align="center">📫 Reach me on</h2>
<p align="center">
  <a target="_blank"href="https://www.linkedin.com/in/abudiseid071/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a target="_blank"href="https://twitter.com/abudialfarah"><img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="mailto:abduseid28+git@gmail.com?subject=Hello%20Ileri,%20From%20Github"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<hr>

<h2  align="center">💻 Buy me coffee ⬇️ </h2>
<html>
  <body>
<div id="smart-button-container">
      <div style="text-align: center;">
        <div id="paypal-button-container"></div>
      </div>
    </div>
  <script src="https://www.paypal.com/sdk/js?client-id=sb&enable-funding=venmo&currency=USD" data-sdk-integration-source="button-factory"></script>
  <script>
    function initPayPalButton() {
      paypal.Buttons({
        style: {
          shape: 'rect',
          color: 'gold',
          layout: 'vertical',
          label: 'paypal',
          
        },

        createOrder: function(data, actions) {
          return actions.order.create({
            purchase_units: [{"description":"Buy me Coffee","amount":{"currency_code":"USD","value":1}}]
          });
        },

        onApprove: function(data, actions) {
          return actions.order.capture().then(function(orderData) {
            
            // Full available details
            console.log('Capture result', orderData, JSON.stringify(orderData, null, 2));

            // Show a success message within this page, e.g.
            const element = document.getElementById('paypal-button-container');
            element.innerHTML = '';
            element.innerHTML = '<h3>Thank you for your payment!</h3>';

            // Or go to another URL:  actions.redirect('thank_you.html');
            
          });
        },

        onError: function(err) {
          console.log(err);
        }
      }).render('#paypal-button-container');
    }
    initPayPalButton();
  </script>
  </body>
  </html>
