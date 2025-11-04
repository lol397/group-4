# group-4
web assigment
Absalat Getenet
Melunay
Hana Tekalegn
Abigiya Emana
Fikir Ashenafi
Tilat Abera
Efrata
Tihitina 
Dawit Meles
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Booking</title>
  <style>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: white;
  color: #333;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  padding: 2rem;
}

@media (min-width: 992px) {
  .container {
    flex-direction: row;
    justify-content: space-around;
  }
}<\style>
</head>
<body>
  <section class="container">
    <div class="left">
      <div class="circle-bg"></div>
      <div class="phone">
        <div class="notch"></div>
        <div class="header">
          <img src="avatar.jpg" alt="Avatar" class="avatar" />
          <div>
            <h4>Samuel Green</h4>
            <p>Available to walk</p>
          </div>
          <span class="menu">⋮</span>
        </div>
        <div class="chat">
<div class="msg purple">That sounds great, I'd be happy with that.</div>
<div class="msg purple">Could you send over some pictures of your dog, please?</div>
<div class="img-row">
<img src="dog1.jpg" alt="dog1" />
<img src="dog2.jpg" alt="dog2" />
<img src="dog3.jpg" alt="dog3" />
</div>
<div class="msg white">Here are a few pictures. She's a happy girl</div>
<div class="msg gray">Can you make it?</div>
<div class="msg purple">She looks so happy! The time we discussed works. How long shall I take her out for?</div>
<div class="options">
<div class="option"><span>30 minute walk</span><strong>$29</strong></div>
<div class="option"><span>1 hour walk</span><strong>$49</strong></div>
</div>
<div class="input">
<input type="text" placeholder="Type a message..." />
<button>›</button>
</div>
</div>
</div>
</div>
<div class="right">
<h1>Simple booking</h1>
<p>
Stay in touch with our dog walkers through the chat interface.
This makes it easy to discuss arrangements and make bookings.
Once the walk has been completed you can rate your walker and
book again all through the chat.
</p>
</div>
</section>
</body>
</html>
