# Mywebsite
HTML-AP CSp
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Lincoln Ryniec — My Future & Units</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 20px; background: #f3f6ff; }
    h1 { margin-top: 0; }
    .card { background: #fff; padding: 16px; margin: 16px 0; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    .vocab-list { list-style-type: none; padding: 0; }
    .vocab-list li { margin: 6px 0; padding: 8px; background: #f9fbff; border: 1px solid #e0e6f5; border-radius: 6px; }
    figure { margin: 0 0 16px 0; }
    figure img { width: 100%; border-radius: 8px; }
    figcaption { font-size: 0.9em; color: #555; margin-top: 4px; }
    iframe { width: 100%; height: 400px; border: none; border-radius: 8px; }
  </style>
</head>
<body>
  <h1>Lincoln Ryniec</h1>
  <p><strong>What I want to do after high school:</strong> I want to be an engineer of some type. I’m interested in solving real-world problems and applying math, science, and design skills to build systems that help people.</p>

  <div class="card">
    <h2>Unit 1: Data</h2>
    <ul class="vocab-list">
      <li><strong>bit:</strong> A binary digit, either 0 or 1.</li>
      <li><strong>byte:</strong> A sequence of 8 bits.</li>
      <li><strong>roundoff:</strong> Error that results when the number of bits is not enough to represent the number with full precision.</li>
      <li><strong>analog data:</strong> Values that change smoothly, rather than in discrete intervals, over time.</li>
      <li><strong>lossless:</strong> Compressing data in a way that preserves all data and allows full recovery of the original.</li>
      <li><strong>lossy:</strong> Compressing data in a way that discards some data and makes it impossible to recover the original.</li>
      <li><strong>metadata:</strong> Data about data, like descriptive information about a file or database row.</li>
    </ul>
  </div>

  <div class="card">
    <h2>Unit 2: Computer Systems and Networks – Review</h2>
    <ul class="vocab-list">
      <li><strong>Computing Device:</strong> A physical device that can run a program (e.g., computer, smartphone).</li>
      <li><strong>Computer Network:</strong> A group of interconnected computing devices capable of sending or receiving data.</li>
      <li><strong>Path:</strong> The series of connections between computing devices on a network.</li>
      <li><strong>Protocol:</strong> An agreed-upon set of rules for communication.</li>
      <li><strong>Fault Tolerant:</strong> A system’s ability to continue functioning even if components fail.</li>
      <li><strong>Scalability:</strong> The ability of a system to expand or contract to meet new demands.</li>
      <li><strong>Bandwidth:</strong> Maximum transmission capacity of a system, measured by bit rate.</li>
      <li><strong>URL:</strong> An easy-to-remember web address (e.g., www.example.com).</li>
      <li><strong>Physical Network:</strong> The hardware and physical connections that carry internet signals.</li>
      <li><strong>Internet Protocol (IP):</strong> Assigns unique addresses and routes data.</li>
      <li><strong>TCP:</strong> Ensures reliable, ordered delivery of data packets.</li>
      <li><strong>UDP:</strong> A faster alternative to TCP with minimal error-checking.</li>
      <li><strong>Packets:</strong> Small chunks of data into which larger messages are divided.</li>
      <li><strong>Routers:</strong> Specialized computers that forward data across networks.</li>
      <li><strong>DNS:</strong> Translates domain names into IP addresses.</li>
      <li><strong>HTTP:</strong> Used for transmitting and requesting web pages.</li>
      <li><strong>WWW:</strong> A system of linked pages and media browsable over HTTP.</li>
      <li><strong>Message Delivery:</strong> Messages are split into packets that may take different paths.</li>
      <li><strong>Redundancy:</strong> Multiple pathways exist so packets can reroute if one path fails.</li>
      <li><strong>Fault Tolerance:</strong> The internet can keep working even if parts are damaged.</li>
      <li><strong>Scalability:</strong> The internet is designed to grow and support billions of devices.</li>
      <li><strong>IPv4:</strong> Uses 32-bit addresses (≈ 4.3 billion unique addresses).</li>
      <li><strong>IPv6:</strong> Adds 16 more bits, vastly expanding address space.</li>
    </ul>
  </div>

  <div class="card">
    <h2>Images (Unit 1 & Unit 2 topics)</h2>
    <figure>
      <img src="https://picsum.photos/id/1005/800/400" alt="Engineer working on design">
      <figcaption>Unit 1: Data and design — representing information and solving problems.</figcaption>
    </figure>
    <figure>
      <img src="https://picsum.photos/id/1011/800/400" alt="Network cables and servers">
      <figcaption>Unit 2: Networks and internet infrastructure.</figcaption>
    </figure>
  </div>

  <div class="card">
    <h2>Video: How the Internet Works</h2>
    <iframe src="https://www.youtube.com/embed/3QhU9jd03a0" title="How the Internet Works"></iframe>
  </div>

  <footer>
    <p>Made by Lincoln Ryniec</p>
  </footer>
</body>
</html>

