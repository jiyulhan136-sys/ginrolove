<!-- CYBERPUNK GLITCH TERMINAL -->

<div align="center">

<svg width="650" height="100" viewBox="0 0 650 100" xmlns="http://www.w3.org/2000/svg">

  <defs>

```
<!-- Neon Glow -->
<filter id="neon">
  <feGaussianBlur stdDeviation="2.5" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>

<!-- Glitch Effect -->
<filter id="glitch">

  <feOffset in="SourceGraphic" dx="-3" dy="0" result="red"/>
  <feOffset in="SourceGraphic" dx="3" dy="0" result="cyan"/>

  <feFlood flood-color="#ff00ff" result="magentaColor"/>
  <feFlood flood-color="#00ffff" result="cyanColor"/>

  <feComposite in="magentaColor" in2="red" operator="in" result="magenta"/>
  <feComposite in="cyanColor" in2="cyan" operator="in" result="cyan"/>

  <feMerge>
    <feMergeNode in="magenta"/>
    <feMergeNode in="cyan"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>

</filter>
```

  </defs>

  <!-- Terminal Frame -->

<rect
 x="5"
 y="5"
 width="640"
 height="90"
 rx="10"
 fill="#050510"
 stroke="#00E5FF"
 stroke-width="1"
 opacity="0.95"
/>

  <!-- Scanlines -->

  <g opacity="0.08">

```
<line x1="5" y1="20" x2="645" y2="20" stroke="#00E5FF"/>
<line x1="5" y1="35" x2="645" y2="35" stroke="#00E5FF"/>
<line x1="5" y1="50" x2="645" y2="50" stroke="#00E5FF"/>
<line x1="5" y1="65" x2="645" y2="65" stroke="#00E5FF"/>
<line x1="5" y1="80" x2="645" y2="80" stroke="#00E5FF"/>
```

  </g>

  <!-- Terminal Prefix -->

<text
x="30"
y="58"
font-family="monospace"
font-size="22"
font-weight="bold"
fill="#9D4EDD"
filter="url(#neon)"

>

```
&gt;_
```

  </text>

  <!-- Loading -->

<text
x="75"
y="58"
font-family="monospace"
font-size="22"
font-weight="bold"
fill="#00E5FF"
filter="url(#neon)"

>

```
<tspan>

  <animate
    attributeName="opacity"
    values="0;1;1;1;0"
    keyTimes="0;0.05;0.65;0.82;0.9"
    dur="9s"
    repeatCount="indefinite"
  />

  [Loading...]

</tspan>
```

  </text>

  <!-- Access Granted -->

<text
x="75"
y="58"
font-family="monospace"
font-size="22"
font-weight="bold"
fill="#00E5FF"
filter="url(#glitch)"

>

```
<tspan>

  <animate
    attributeName="opacity"
    values="0;0;1;1;1;0"
    keyTimes="0;0.30;0.36;0.62;0.70;0.75"
    dur="9s"
    repeatCount="indefinite"
  />

  [Access Granted]

</tspan>
```

  </text>

  <!-- Welcome -->

<text
x="75"
y="58"
font-family="monospace"
font-size="22"
font-weight="bold"
fill="#FFFFFF"
filter="url(#neon)"

>

```
<tspan>

  <animate
    attributeName="opacity"
    values="0;0;0;1;1;1;0"
    keyTimes="0;0.62;0.68;0.73;0.86;0.92;0.98"
    dur="9s"
    repeatCount="indefinite"
  />

  [Welcome]

</tspan>
```

  </text>

  <!-- Blinking Cursor -->

<rect
x="255"
y="38"
width="3"
height="25"
fill="#00E5FF"
filter="url(#neon)"

>

```
<animate
  attributeName="opacity"
  values="1;0;1"
  dur="0.8s"
  repeatCount="indefinite"
/>
```

  </rect>

  <!-- Glitch Bars -->

  <g opacity="0">

```
<rect
  x="100"
  y="42"
  width="140"
  height="3"
  fill="#FF00FF"
/>

<rect
  x="300"
  y="62"
  width="180"
  height="2"
  fill="#00FFFF"
/>

<animate
  attributeName="opacity"
  values="0;0;1;0;0;1;0"
  keyTimes="0;0.32;0.34;0.36;0.68;0.70;0.72"
  dur="9s"
  repeatCount="indefinite"
/>
```

  </g>

</svg>

<br>

`[ SYSTEM ONLINE ]`　`[ CONNECTION ESTABLISHED ]`

</div>
