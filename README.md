# matkabday
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Countdown</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@700&family=Raleway:wght@300&display=swap');

    body {
      background: radial-gradient(circle at top, #000000, #0a0a0a 70%);
      color: #e0e0e0;
      font-family: 'Raleway', sans-serif;
      text-align: center;
      padding: 0;
      margin: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      overflow: hidden;
    }

    h1 {
      font-family: 'Cinzel Decorative', serif;
      font-size: 3rem;
      letter-spacing: 4px;
      color: #ff4444;
      margin-bottom: 30px;
      text-shadow: 0 0 20px rgba(255, 0, 0, 0.8);
    }

    #countdown {
      font-size: 2rem;
      letter-spacing: 2px;
      background: rgba(0,0,0,0.4);
      padding: 20px 40px;
      border: 2px solid #ff4444;
      border-radius: 10px;
      display: inline-block;
      box-shadow: 0 0 15px rgba(255, 0, 0, 0.5);
    }

    .fog {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: url('https://www.transparenttextures.com/patterns/foggy-birds.p
