</head>
<body>

<h1>Wi-Fi Network Exploitation & Security Measures</h1>

   <div class="disclaimer">
        <h2>Disclaimer</h2>
        <p><strong>⚠️ This project was done for educational purposes only.</strong> Keep in mind that I created a subnet to launch this attack against. Performing this kind of activity on networks you do not own without permission is considered <span class="important">illegal.</span></p>
    </div>

   <h2>Project Introduction</h2>
    <h3>The end goal of this project is to:</h3>
    <p>Utilize a <strong>Flipper Zero</strong> with an <strong>ESP32 Marauder</strong> board to analyze and capture Wi-Fi network traffic packets through a de-authorization attack. The collected packets will then be converted into a hash, which will be cracked using <strong>Hashcat</strong> through a dictionary attack.</p>

   <h3>Tools and IoT Devices Used:</h3>
    <ul>
        <li>Flipper Zero</li>
        <li>ESP32 Marauder Wi-Fi board</li>
        <li>Kali Linux</li>
        <li>Wireshark</li>
        <li><a href="https://hashcat.net/cap2hashcat/" target="_blank">cap2hashcat</a></li>
        <li>Hashcat</li>
        <li>Rockyou.txt</li>
    </ul>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>

   <h2>Project Demonstration</h2>
    <p>Watch the video demonstration of the project below:</p>
<!DOCTYPE html>
<html lang="en">
[![Watch the video](https://img.youtube.com/vi/tBvd7weNN0g/0.jpg)](https://www.youtube.com/watch?v=tBvd7weNN0g)


   <h2>Further Possibilities of this Exploitation</h2>
    <p>While I only cracked the password of a Wi-Fi network, this can be seen as the first step toward more severe exploits. If someone gains unauthorized access to your Wi-Fi network, it could lead to serious security risks, including:</p>

  <ul>
        <li><strong>Data Interception:</strong> Attackers can intercept sensitive information such as passwords, personal messages, and financial data.</li>
        <li><strong>Bandwidth Theft:</strong> Unauthorized users can slow down your internet speed and even cause overage charges from your ISP.</li>
        <li><strong>Malware Distribution:</strong> An attacker could spread malware across your network, compromising connected devices.</li>
        <li><strong>Network Attacks:</strong> Unauthorized users can use your connection to launch attacks on other devices or external targets.</li>
        <li><strong>Privacy Breach:</strong> Attackers can monitor your online activity and gather personal information for malicious purposes.</li>
        <li><strong>Access to Connected Devices:</strong> Weak network security can allow attackers to control smart devices like cameras or home automation systems.</li>
    </ul>

   <h2>How to Address and Prevent De-authentication Attacks</h2>
    <p>To protect your Wi-Fi network from de-authentication attacks and packet sniffing, implement the following security measures:</p>

   <ul>
        <li><strong>Use WPA3 Encryption:</strong> Upgrade your Wi-Fi security to <strong>WPA3</strong> if supported. It offers stronger protection compared to WPA2.</li>
        <li><strong>Strong Passwords:</strong> Use complex passwords (12-16 characters long) and avoid common phrases.</li>
        <li><strong>Disable WPS:</strong> Wi-Fi Protected Setup (WPS) is vulnerable to attacks. Turn it off in your router settings.</li>
        <li><strong>Regular Firmware Updates:</strong> Keep your router firmware updated to patch known security vulnerabilities.</li>
        <li><strong>MAC Address Filtering:</strong> Restrict network access to known devices using MAC filtering (though not foolproof).</li>
        <li><strong>Network Segmentation:</strong> Create separate networks for guests and IoT devices to limit potential exposure.</li>
        <li><strong>Disable SSID Broadcasting:</strong> Hiding your SSID makes your network less visible to casual users.</li>
        <li><strong>Use a VPN:</strong> Encrypt internet traffic using a Virtual Private Network (VPN), especially on public networks.</li>
        <li><strong>Intrusion Detection/Prevention Systems (IDS/IPS):</strong> Monitor suspicious activity and respond to threats in real time.</li>
        <li><strong>Limit Signal Range:</strong> Adjust router settings to reduce the Wi-Fi signal range outside your property.</li>
        <li><strong>Disable Remote Management:</strong> Turn off remote management features unless absolutely necessary.</li>
        <li><strong>Monitor Network Traffic:</strong> Regularly check for unauthorized devices or unusual traffic patterns.</li>
    </ul>

  <p>Implementing these measures will significantly improve the security of your Wi-Fi network against <strong>de-authentication attacks</strong> and <strong>packet sniffing</strong>.</p>

</body>
</html>
[![Watch the video](https://img.youtube.com/vi/tBvd7weNN0g/0.jpg)](https://www.youtube.com/watch?v=tBvd7weNN0g)

