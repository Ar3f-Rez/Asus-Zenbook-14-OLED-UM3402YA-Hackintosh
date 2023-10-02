# Asus-Zenbook-14-OLED-UM3402YA-Hackintosh

Hackintosh

## macOS Version Support:
<table>
  <thead>
    <tr>
      <th>macOS Version</th>
      <th colspan=2>Status</th>
      <th>Minimum version</th>
      <th>Maximum version</th>
    </tr>
  </thead>
  <tbody>
  <!-- macOS 13 -->
    <tr>
      <td>
        <img
          src="https://raw.githubusercontent.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/main/docs/assets/README/ventura.png"
          width=25
          hspace=2
          align="top"
        />
        Ventura
      </td>
      <td style="text-align: center;">✅</td>
      <td>Work in Progress.</td>
      <td><code>(None)</code></td>
      <td><a href="https://apps.apple.com/us/app/macos-ventura/id1638787999"><code>(Latest)</code></a></td>
    </tr>


### Hardware Features:

<table>
  <thead>
    <tr>
      <th>Component</th>
      <th>Device</th>
      <th colspan=2>Status</th>
    </tr>
  </thead>
  <tbody>
  <!-- Processor -->
    <tr>
      <td>CPU</td>
      <td>• Ryzen 7 5825U</td>
      <td style="text-align: center;">✅</td>
      <td>Natively supported (since macOS Ventura).</td>
    </tr>
  <!-- Graphics -->
    <tr>
      <td rowspan=1>Graphics</td>
      <td>AMD Radeon RX Vega 8</td>
      <td style="text-align: center;">✅</td>
      <td>Full acceleration (thanks to NootedRed).</td>
    </tr>
  <!-- Displays -->
    <tr>
      <td rowspan=1>Displays</td>
      <td>14" Primary Display<br>(2.8K OLED display @ 90 Hz)</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with backlight control).</td>
    </tr>
  <!-- Interfaces -->
    <tr>
      <td rowspan=6>Interfaces</td>
      <td>Built-in Keyboard</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with media keys and backlight control).</td>
    </tr>
    <tr>
      <td>Built-in Trackpad</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (GPIO pinned with multi-touch gestures)</td>
    </tr>
    <tr>
      <td>(Physical) Trackpad Buttons</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in progress (VoodooI2C issue; incorrect button map).</td>
    </tr>
    <tr>
      <td rowspan=2>Touchscreen<br>(Primary Display)<br>(Screenpad Plus Display)</td>
      <td style="text-align: center;">✅</td>
      <td rowspan=2>Fully supported (GPIO pinned with multi-touch gestures)</td>
    </tr>
    <tr>
      <td style="text-align: center;">✅</td>
    </tr>
    <tr>
      <td>Capacitive Stylus</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in progress (works without pressure data).</td>
    </tr>
  <!-- Audio -->
    <tr>
      <td rowspan=2>Audio<br>(Realtek ALC294)</td>
      <td>Built-in speakers</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in Progress.</td>
    </tr>
    <tr>
      <td>Built-in microphone</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in Progress</td>
    </tr>
  <!-- Camera -->
    <tr>
      <td>Camera</td>
      <td>Windows Hello HD Camera</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported.</td>
    </tr>
  <!-- Wi-Fi + Bluetooth -->
    <tr>
      <td>Wi-Fi</td>
      <td rowspan=2>(Upgraded)Intel AX211<br>(Wi-Fi 6 + Bluetooth 5.0)</td>
      <td rowspan=2 style="text-align: center;">✅</td>
      <td rowspan=2>Fully supported (with limited Continuity support).</td>
    </tr>
    <tr>
      <td>Bluetooth</td>
    </tr>
  <!-- Storage -->
    <tr>
      <td>Storage</td>
      <td>Intel 660p NVMe SSD</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with power management).</td>
    </tr>
  <!-- Ports -->
    <tr>
      <td>Ports</td>
      <td>USB Mapped and ports are working fine</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported.</td>
    </tr>
  <!-- Battery and Power -->
    <tr>
      <td rowspan=2>Battery</td>
      <td>Built-in Battery</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with power reading).</td>
    </tr>
    <tr>
      <td>AC Power Adapter</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with hotplug and charge limit feature).</td>
    </tr>
  </tbody>
</table>
  
