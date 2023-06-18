<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Working HTML File</title>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
    }
    .social {
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: center;
    }
.social a {
  display: flex;
  align-items: center;
  text-decoration: none;
  margin-right: 10px; 
}
.social a img {
  width: 30px;
  height: 30px;
  background: none;
  transition: all 0.3s ease;
}
.social a span {
  display: none;
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translateX(-50%);
  margin-top: 5px;
  font-family: 'Roboto', sans-serif;
  font-size: 16px;
  font-weight: bold;
  color: #00b3b3;
  white-space: nowrap;
}
.social a:hover img {
  width: 40px;
  height: 40px;
}
.social a:hover span {
  display: block;
}
footer {
  background: linear-gradient(to bottom, #ffffff, #00b3b3);
  padding: 35px;
  color: #ffffff;
  text-align: center;
  font-size: 14px;
}
.footer-container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
.footer-container .box {
  background-color: #00b3b3;
  color: #ffffff;
  border-radius: 10px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  padding: 20px;
  text-align: center;
  margin: 10px;
  cursor: pointer;
}
.footer-container .box h3 {
  font-size: 18px;
  margin: 0;
  color: #ffffff;
}
.footer-container .box p {
  font-size: 14px;
  margin: 10px 0 0;
  color: #ffffff;
}
.footer-container .box:first-child {
  border: 1px solid #ffffff;
}
.footer-container .box:last-child {
  border: 1px solid #ffffff;
}
.tcbhg {
  text-align: center;
  margin-top: 20px;
}
.tcbhg a {
  color: white;
  text-decoration: none;
}
.tcbhg a:hover {
  text-decoration: underline;
}
.back-to-top {
  background-color: #00b3b3;
  color: #ffffff;
  border: none;
  padding: 2px 4px;
  border-radius: 30px;
  font-family: 'Roboto', sans-serif;
  font-size: 10px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 1px;
  cursor: pointer;
  outline: none;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: background-color 0.3s ease-in-out, transform 0.2s ease-in-out;
}
.back-to-top:hover {
  background-color: #008080;
  transform: scale(1.05);
}
.back-to-top:active {
  transform: scale(0.95);
}
.new-heading {
  font-size: 18px;
  color: #00b3b3;
  margin-top: 0;
}
.new-heading+p {
  font-size: 10px;
  margin-bottom: 10px;
  color: #00b3b3;
}
.cta-button {
  display: inline-block;
  background-color: #00b3b3;
  color: #ffffff;
  border: none;
  padding: 2px 4px;
  border-radius: 14px;
  font-family: 'Roboto', sans-serif;
  font-size: 10px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 1px;
  cursor: pointer;
  outline: none;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: background-color 0.3s ease-in-out, transform 0.2s ease-in-out;
  text-decoration: none;
  margin-bottom: 10px;
}
.cta-button:hover {
  background-color: #008080;
  transform: scale(1.05);
}
.cta-button:active {
  transform: scale(0.95);
}
.guide-to-copywriting {
  color: #FF0000;
  font-size: 16px;
  font-weight: bold;
} </style>
</head><body>
  <footer>
    <div class="footer-container">
      <div class="box">
        <h3>Contact</h3>
        <p>Email: contact@thehub.com</p>
      </div>
      <div class="box">
  <h3>Terms and conditions</h3>
  <p>By using The Hub, you agree to our <a href="https://example.com/terms" style="color: pink;">Terms of Service</a> and Privacy Policy. Please read them carefully before accessing or using our platform.</p>
</div>
      <div class="box" onclick="window.location.href = 'https://oavo33.github.io/GitHubz/';">
        <h3>What Do You Think About Our Community Hub?</h3>
      </div><div class="box">
        <h3>Follow Us</h3>
        <div class="social">
          <a href="#">
            <img src="https://img.icons8.com/office/30/FF0000/youtube.png" alt="YouTube">
          </a>
          <a href="#">
            <img src="https://img.icons8.com/office/30/FF0000/facebook-new.png" alt="Facebook">
          </a>
        </div>
      </div>
      <div class="box back-to-top" onclick="scrollToTop()">To The Top</div><p>&copy; 2023 Lofties. All rights reserved.</p>
    </div>
    <div class="tcbhg">
      <p>
        <a href="https://example.com/privacy-policy">Privacy Policy</a>
      </p>
      <p>
        <a href="https://example.com/guide-to-copywriting" class="guide-to-copywriting">The Community Business Hub's Guide To Copywriting</a>
      </p>
    </div>
  </footer><script>
    function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    </script>
</body>

</html>
