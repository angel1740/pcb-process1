# pcb-process1
Online PCB Checklist Form
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PCB Fabrication Checklist</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f4f4f4;
    }
    h2 {
      color: #333;
    }
    .section {
      margin-bottom: 20px;
      background: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .section label {
      display: inline-block;
      margin-bottom: 8px;
      margin-right: 15px;
    }
    input[type="text"], input[type="email"] {
      margin-top: 5px;
      margin-bottom: 10px;
      padding: 6px;
      width: 300px;
    }
    button {
      padding: 10px 15px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h2></h2>

  <form id="pcbForm" action="https://formsubmit.co/angel@lingkeypcba.com" method="POST">





    
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PCB Fabrication Checklist</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f4f4f4;
    }
    h2 {
      color: #333;
    }
    .section {
      margin-bottom: 20px;
      background: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .section label {
      margin-right: 15px;
      display: inline-block;
      margin-bottom: 5px;
    }
    .output {
      white-space: pre-wrap;
      background: #e6f7ff;
      padding: 10px;
      border: 1px solid #91d5ff;
      border-radius: 6px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h2>PCB Fabrication Checklist</h2>
  <form id="pcbForm">
    <div class="section">
      <strong>Base Material:</strong><br />
      <label><input type="checkbox" name="Base Material" value="FR-4" /> FR-4</label>
      <label><input type="checkbox" name="Base Material" value="FPC（Flex）" /> FPC（Flex）</label>
      <label><input type="checkbox" name="Base Material" value="Aluminum" /> Aluminum</label>
      <label><input type="checkbox" name="Base Material" value="Copper Core" /> Copper Core</label>
      <label><input type="checkbox" name="Base Material" value="Rogers" /> Rogers</label>
      <label><input type="checkbox" name="Base Material" value="Ceramics" /> Ceramics</label>
    </div>

    <div class="section">
      <strong>Layers:</strong><br />
      <label><input type="checkbox" name="Layers" value="1" /> 1</label>
      <label><input type="checkbox" name="Layers" value="2" /> 2</label>
      <label><input type="checkbox" name="Layers" value="4" /> 4</label>
      <label><input type="checkbox" name="Layers" value="6" /> 6</label>
      <label><input type="checkbox" name="Layers" value="8" /> 8</label>
      <label><input type="checkbox" name="Layers" value="10" /> 10</label>
      <label><input type="checkbox" name="Layers" value="12" /> 12</label>
      <label><input type="checkbox" name="Layers" value="14" /> 14</label>
      <label><input type="checkbox" name="Layers" value="16" /> 16</label>
      <label><input type="checkbox" name="Layers" value="18" /> 18</label>
      <label><input type="checkbox" name="Layers" value="20" /> 20</label>
    </div>

    <div class="section">
      <strong>Dimensions (mm):</strong><br />
      Length: <input type="text" name="Length" placeholder="e.g. 100" />
      Width: <input type="text" name="Width" placeholder="e.g. 50" />
    </div>

    <div class="section">
      <strong>PCB Qty:</strong><br />
      <input type="text" name="PCB Qty" placeholder="e.g. 5" />
    </div>

    <div class="section">
      <strong>PCB Thickness:</strong><br />
      <label><input type="checkbox" name="Thickness" value="0.2mm" /> 0.2mm</label>
      <label><input type="checkbox" name="Thickness" value="0.4mm" /> 0.4mm</label>
      <label><input type="checkbox" name="Thickness" value="0.6mm" /> 0.6mm</label>
      <label><input type="checkbox" name="Thickness" value="0.8mm" /> 0.8mm</label>
      <label><input type="checkbox" name="Thickness" value="1.0mm" /> 1.0mm</label>
      <label><input type="checkbox" name="Thickness" value="1.2mm" /> 1.2mm</label>
      <label><input type="checkbox" name="Thickness" value="1.6mm" /> 1.6mm</label>
      <label><input type="checkbox" name="Thickness" value="2.0mm" /> 2.0mm</label>
    </div>

    <div class="section">
      <strong>PCB Color:</strong><br />
      <label><input type="checkbox" name="Color" value="Green" /> Green</label>
      <label><input type="checkbox" name="Color" value="Yellow" /> Yellow</label>
      <label><input type="checkbox" name="Color" value="Blue" /> Blue</label>
      <label><input type="checkbox" name="Color" value="Red" /> Red</label>
      <label><input type="checkbox" name="Color" value="White" /> White</label>
      <label><input type="checkbox" name="Color" value="Black" /> Black</label>
    </div>

    <div class="section">
      <strong>Silkscreen:</strong><br />
      <label><input type="checkbox" name="Silkscreen" value="White" /> White</label>
      <label><input type="checkbox" name="Silkscreen" value="Black" /> Black</label>
    </div>

    <div class="section">
      <strong>Surface Finish:</strong><br />
      <label><input type="checkbox" name="Surface Finish" value="HASL (with lead)" /> HASL (with lead)</label>
      <label><input type="checkbox" name="Surface Finish" value="LeadFree HASL" /> LeadFree HASL</label>
      <label><input type="checkbox" name="Surface Finish" value="Gold plating" /> Gold plating</label>
      <label><input type="checkbox" name="Surface Finish" value="Nickel plat" /> Nickel plat</label>
      <label><input type="checkbox" name="Surface Finish" value="flux goating" /> flux goating</label>
      <label><input type="checkbox" name="Surface Finish" value="flash gold" /> flash gold</label>
      <label><input type="checkbox" name="Surface Finish" value="immersion gold" /> immersion gold</label>
      <label><input type="checkbox" name="Surface Finish" value="immersion tin" /> immersion tin</label>
      <label><input type="checkbox" name="Surface Finish" value="immersion silver" /> immersion silver</label>
      <label><input type="checkbox" name="Surface Finish" value="OSP" /> OSP</label>
    </div>

    <div class="section">
      <strong>Outer Copper Weight:</strong><br />
      <label><input type="checkbox" name="Copper Weight" value="0.5 oz" /> 0.5 oz</label>
      <label><input type="checkbox" name="Copper Weight" value="1 oz" /> 1 oz</label>
      <label><input type="checkbox" name="Copper Weight" value="2 oz" /> 2 oz</label>
    </div>

    <div class="section">
      <strong>Via Covering:</strong><br />
      <label><input type="checkbox" name="Via Covering" value="Tented" /> Tented</label>
      <label><input type="checkbox" name="Via Covering" value="Untented" /> Untented</label>
      <label><input type="checkbox" name="Via Covering" value="Plugged" /> Plugged</label>
      <label><input type="checkbox" name="Via Covering" value="Epoxy Filled & Capped" /> Epoxy Filled & Capped</label>
    </div>

    <div class="section">
      <strong>Min via hole size/diameter:</strong><br />
      <label><input type="checkbox" name="Min Hole Size" value="0.3mm(0.4/0.45)" /> 0.3mm(0.4/0.45)</label>
      <label><input type="checkbox" name="Min Hole Size" value="0.25mm(0.35)" /> 0.25mm(0.35)</label>
      <label><input type="checkbox" name="Min Hole Size" value="0.2mm(0.3/0.35)" /> 0.2mm(0.3/0.35)</label>
      <label><input type="checkbox" name="Min Hole Size" value="0.15mm(0.25/0.3)" /> 0.15mm(0.25/0.3)</label>
    </div>

    <div class="section">
      <strong>Tolerance:</strong><br />
      <label><input type="checkbox" name="Tolerance" value="±0.2mm" /> ±0.2mm</label>
      <label><input type="checkbox" name="Tolerance" value="±0.1mm" /> ±0.1mm</label>
    </div>

    <div class="section">
      <strong>Electrical Test:</strong><br />
      <label><input type="checkbox" name="Electrical Test" value="Yes" /> Yes (Flying Probe Fully Test)</label>
      <label><input type="checkbox" name="Electrical Test" value="No" /> No</label>
    </div>

    <div class="section">
      <strong>Gold Fingers:</strong><br />
      <label><input type="checkbox" name="Gold Fingers" value="Yes" /> Yes</label>
      <label><input type="checkbox" name="Gold Fingers" value="No" /> No</label>
    </div>

    <div class="section">
      <strong>Castellated Holes:</strong><br />
      <label><input type="checkbox" name="Castellated Holes" value="Yes" /> Yes</label>
      <label><input type="checkbox" name="Castellated Holes" value="No" /> No</label>
    </div>

    <div class="section">
      <strong>Edge Plating:</strong><br />
      <label><input type="checkbox" name="Edge Plating" value="Yes" /> Yes</label>
      <label><input type="checkbox" name="Edge Plating" value="No" /> No</label>
    </div>

    <div class="section">
      <strong>Blind Slots:</strong><br />
      <label><input type="checkbox" name="Blind Slots" value="Yes" /> Yes</label>
      <label><input type="checkbox" name="Blind Slots" value="No" /> No</label>
    </div>

    <div class="section">
      <strong>Delivery Format:</strong><br />
      <label><input type="checkbox" name="Delivery Format" value="Single PCB" /> Single PCB</label>
      <label><input type="checkbox" name="Delivery Format" value="Panel by Customer" /> Panel by Customer</label>
      <label><input type="checkbox" name="Delivery Format" value="Panel by Factory" /> Panel by Factory</label>
    </div>

    <div class="section">
    <button type="button" onclick="submitForm()">Submit</button>
  </form>
  <pre id="output" style="white-space: pre-wrap; margin-top: 20px;"></pre>

  <script>
    function submitForm() {
      const form = document.getElementById('pcbForm');
      const data = new FormData(form);
      const output = [];
      for (const [key, value] of data.entries()) {
        output.push(`${key}: ${value}`);
      }
      document.getElementById('output').innerText = output.join('\n');
    }
  </script>
</body>
</html>

    
    
    
    
    
    
    <div class="section">
      <label>Surface technology (copy and paste):</label><br/>
      <input type="text" name="Surface technology (copy and paste)" id="summaryBox" required />
    </div>

    <div class="section">
      <label>Your Email:</label><br/>
      <input type="email" name="Email" required />
    </div>
    
    

    <!-- 隐藏项 -->
    <input type="hidden" name="_captcha" value="false">
    
    
    
    <div class="section">
      <button type="button" onclick="generateSummary()">1. Generate Summary</button>
      <button type="submit">2. Submit to Email</button>
    </div>
  </form>

  <script>
    function generateSummary() {
      const form = document.getElementById('pcbForm');
      const formData = new FormData(form);
      const result = {};

      for (const [key, value] of formData.entries()) {
        if (!result[key]) {
          result[key] = [value];
        } else {
          result[key].push(value);
        }
      }

      let summary = '';
      for (const key in result) {
        if (key.startsWith('_')) continue; // Skip hidden inputs
        summary += `${key}: ${result[key].join(', ')}\n`;
      }

      document.getElementById('summaryBox').value = summary.trim();
    }
  </script>
</body>
</html>
