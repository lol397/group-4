# group-4
web assigment
Absalat Getenet
Melunay
Hana Tekalegn
Abigiya Emana
Fikir Ashenafi
Tsilat Abera
Efrata solomon
Tihitina Getahun
Dawit Meles
Bathseba Taklit
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
* {
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
}
  .notch {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 120px;
  height: 20px;
  background: #fff;
  border-radius: 0 0 10px 10px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.header {
  background: linear-gradient(135deg, #a855f7, #ec4899);
  color: #fff;
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 15px;
  border-radius: 0 0 20px 20px;
}
.msg {
  border-radius: 15px;
  padding: 10px 15px;
  margin-bottom: 10px;
  max-width: 220px;
  line-height: 1.4;
  font-size: 13px;
}

.msg.purple {
  background: #f3e8ff;
}

.msg.white {
  background: white;
  border: 1px solid #eee;
  margin-left: auto;
}

.msg.gray {
  background: #f3f3f3;
  margin-left: auto;
}

.img-row {
  display: flex;
  gap: 8px;
  margin-bottom: 10px;
}

.img-row img {
  width: 60px;
  height: 60px;
  border-radius: 10px;
  object-fit: cover;
}
.options {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin: 15px 0;
}

.option {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: linear-gradient(135deg, #a855f7, #ec4899);
  color: white;
  border-radius: 25px;
  padding: 10px 20px;
  font-size: 13px;
  cursor: pointer;
}

.input {
  display: flex;
  align-items: center;
  gap: 10px;
}

.input input {
  flex: 1;
  padding: 8px 12px;
  border-radius: 25px;
  border: 1px solid #ccc;
  outline: none;
  font-size: 13px;
}.input button {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  border: none;
  background: #6d28d9;
  color: white;
  font-size: 20px;
  cursor: pointer;
}

/* RIGHT SIDE */
.right {
  max-width: 500px;
  text-align: center;
}

@media (min-width: 992px) {
  .right {
    text-align: left;
  }
}
</style>
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
