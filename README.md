<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Arrow H Beef Order</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      padding: 2rem;
    }
    .container {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      max-width: 600px;
      margin: auto;
    }
    h1 {
      color: #2d6a4f;
    }
    label {
      display: block;
      margin-top: 1rem;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
    }
    .cut-row {
      display: flex;
      gap: 1rem;
      align-items: center;
      margin-top: 0.5rem;
    }
    .cut-row input[type="number"] {
      width: 80px;
    }
    .submit-btn {
      margin-top: 2rem;
      background: #2d6a4f;
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .price-display, .weight-display {
      margin-top: 1rem;
      font-weight: bold;
    }
    .error {
      color: red;
      font-weight: bold;
    }
    .thank-you {
      color: green;
      font-weight: bold;
      margin-top: 1rem;
      display: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Order Arrow H Beef</h1>
    <form id="beefOrderForm">
      <label for="orderSize">Select Order Size</label>
      <select id="orderSize" name="orderSize" required>
        <option value="">Choose one</option>
        <option value="quarter">Quarter Beef (approx. 100 lbs)</option>
        <option value="half">Half Beef (approx. 200 lbs)</option>
        <option value="whole">Whole Beef (approx. 400 lbs)</option>
      </select>

      <label>Preferred Cuts (Enter pounds per cut)</label>
      <div class="cut-row"><label>Tenderloin ($18/lb)</label><input type="number" name="Tenderloin" min="0" placeholder="lbs" data-price="18"></div>
      <div class="cut-row"><label>Ribeye ($16/lb)</label><input type="number" name="Ribeye" min="0" placeholder="lbs" data-price="16"></div>
      <div class="cut-row"><label>New York Strip ($15/lb)</label><input type="number" name="NewYorkStrip" min="0" placeholder="lbs" data-price="15"></div>
      <div class="cut-row"><label>T-Bone / Porterhouse ($17/lb)</label><input type="number" name="TbonePorterhouse" min="0" placeholder="lbs" data-price="17"></div>
      <div class="cut-row"><label>Flat Iron ($14/lb)</label><input type="number" name="FlatIron" min="0" placeholder="lbs" data-price="14"></div>
      <div class="cut-row"><label>Baseball Steak ($13/lb)</label><input type="number" name="BaseballSteak" min="0" placeholder="lbs" data-price="13"></div>
      <div class="cut-row"><label>Flank ($12/lb)</label><input type="number" name="Flank" min="0" placeholder="lbs" data-price="12"></div>
      <div class="cut-row"><la


