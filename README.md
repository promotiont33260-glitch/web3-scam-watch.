<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Web3 Scam Watch</title>
  <style>
    body {margin:0;font-family:Arial, sans-serif;background:#0b0f19;color:#e6ebff}
    header {padding:20px;background:#11172a;text-align:center}
    .container {max-width:1100px;margin:auto;padding:20px}
    .card {background:#11172a;border-radius:12px;padding:20px;margin:15px 0}
    input, textarea, select, button {
      width:100%;padding:10px;margin-top:8px;
      border-radius:6px;border:none;outline:none;
    }
    button {background:#5b8cff;color:white;cursor:pointer}
    button:hover {opacity:.9}
    .tag {display:inline-block;padding:4px 10px;border-radius:20px;background:#5b8cff;margin-right:5px;font-size:12px}
    footer {text-align:center;padding:20px;color:#8fa2ff}
    ul {padding-left:20px}
  </style>
</head>
<body>

<header>
  <h1>Web3 Scam Watch</h1>
  <p>Independent reporting, verification, and community protection for Web3 projects.</p>
</header>

<div class="container">

  <div class="card">
    <h2>Report a Scam Project</h2>
    <form>
      <input type="text" placeholder="Project Name" required>
      <input type="text" placeholder="Contract Address / Wallet Address" required>
      <input type="text" placeholder="Transaction Hash (optional)">
      <select>
        <option>Rug Pull</option>
        <option>Fake Dev</option>
        <option>Phishing</option>
        <option>Impersonation</option>
      </select>
      <textarea rows="4" placeholder="Describe what happened" required></textarea>
      <input type="file">
      <button type="submit">Submit Report</button>
    </form>
    <p style="font-size:12px;color:#8fa2ff;">
      Reports are reviewed before public display. False reports may be rejected.
    </p>
  </div>

  <div class="card">
    <h2>Reported Projects</h2>
    <p><span class="tag">Under Review</span> ExampleToken — 0x123...abc</p>
    <p><span class="tag">Verified Scam</span> FakeMint — 0x456...def</p>
  </div>

  <div class="card">
    <h2>How We Help</h2>
    <ul>
      <li>Collect structured scam reports from the community</li>
      <li>Verify incidents using on-chain evidence and open-source intelligence</li>
      <li>Classify reports as Under Review, Verified Incident, or Resolved</li>
      <li>Publish safety alerts to warn users early</li>
      <li>Support investigation and reporting workflows for affected users (fund recovery is not guaranteed)</li>
    </ul>
  </div>

  <div class="card">
    <h2>For Projects & Dev Teams</h2>
    <p>
      We partner with Web3 projects to help protect their brand, users, and community from scams, impersonation, and malicious actors.
    </p>
    <ul>
      <li>Monitor scam reports involving your project name, contract addresses, and branding</li>
      <li>Identify impersonation attempts and fake links circulating in communities</li>
      <li>Provide periodic safety reports and incident summaries</li>
      <li>Support your moderators with evidence-based scam verification</li>
      <li>Assist affected users with investigation and reporting guidance (fund recovery is not guaranteed)</li>
    </ul>
  </div>

  <div class="card">
    <h2>Disclaimer</h2>
    <p>
      Web3 Scam Watch is an independent community safety initiative. We do not guarantee fund recovery or legal outcomes. 
      Blockchain transactions are irreversible by design. Our role is to support investigation, evidence collection, and responsible reporting.
    </p>
  </div>

</div>

<footer>
  Built for Web3 Safety • Stay Safe
</footer>

</body>
</html>
