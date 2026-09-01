

```aura width=860 height=200 link="https://collectioneur.github.io/readme-aura/"
<div style={{
  width: '100%', height: '100%', background: '#08050F',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(168,85,247,0.30)'
}}>

  <style>{`
      @keyframes float-slow {
        0%, 100% { transform: translateX(0px); opacity: 0.8; }
        50% { transform: translateX(350px); opacity: 1.2; }
      }
      @keyframes float-medium {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(-250px); opacity: 1.1; }
      }
      @keyframes float-fast {
        0%, 100% { transform: translateX(0px); opacity: 0.9; }
        50% { transform: translateX(200px); opacity: 0.6; }
      }
      @keyframes float-diagonal {
        0%, 100% { transform: translateX(0px); opacity: 0.75; }
        50% { transform: translateX(300px); opacity: 1.0; }
      }
      @keyframes float-wave {
        0%, 100% { transform: translateX(0px); opacity: 0.65; }
        33% { transform: translateX(-160px); opacity: 0.9; }
        66% { transform: translateX(80px); opacity: 1.0; }
      }
      @keyframes float-pulse {
        0%, 100% { transform: scale(1); opacity: 0.8; }
        50% { transform: scale(1.3); opacity: 0.4; }
      }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-fast 9s ease-in-out infinite; }
      #glow-4 { animation: float-slow 11s ease-in-out infinite reverse; }
      #glow-5 { animation: float-medium 14s ease-in-out infinite reverse; }
      #glow-6 { animation: float-diagonal 10s ease-in-out infinite; }
      #glow-7 { animation: float-wave 13s ease-in-out infinite; }
      #glow-8 { animation: float-pulse 7s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
  <defs>
    <radialGradient id="g1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stopColor="rgba(168,85,247,0.75)" />
      <stop offset="40%" stopColor="rgba(126,34,206,0.40)" />
      <stop offset="70%" stopColor="rgba(126,34,206,0)" />
    </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,60,255,0.6)" />
        <stop offset="45%" stopColor="rgba(30,50,200,0.25)" />
        <stop offset="70%" stopColor="rgba(30,50,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,130,255,0.45)" />
        <stop offset="50%" stopColor="rgba(0,100,220,0.18)" />
        <stop offset="70%" stopColor="rgba(0,100,220,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,190,230,0.32)" />
        <stop offset="70%" stopColor="rgba(0,190,230,0)" />
      </radialGradient>
      <radialGradient id="g5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(90,30,200,0.38)" />
        <stop offset="70%" stopColor="rgba(90,30,200,0)" />
      </radialGradient>
      <radialGradient id="g6" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.55)" />
        <stop offset="45%" stopColor="rgba(130,20,220,0.22)" />
        <stop offset="70%" stopColor="rgba(130,20,220,0)" />
      </radialGradient>
      <radialGradient id="g7" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(20,60,255,0.42)" />
        <stop offset="50%" stopColor="rgba(10,40,200,0.16)" />
        <stop offset="70%" stopColor="rgba(10,40,200,0)" />
      </radialGradient>
      <radialGradient id="g8" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,170,255,0.40)" />
        <stop offset="50%" stopColor="rgba(0,130,220,0.15)" />
        <stop offset="70%" stopColor="rgba(0,130,220,0)" />
      </radialGradient>
    </defs>

    <ellipse id="glow-1" cx="180" cy="230" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="240" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="240" rx="180" ry="140" fill="url(#g3)" />
    <ellipse id="glow-4" cx="550" cy="250" rx="150" ry="120" fill="url(#g4)" />
    <ellipse id="glow-5" cx="750" cy="250" rx="130" ry="110" fill="url(#g5)" />
    <ellipse id="glow-6" cx="300" cy="240" rx="180" ry="140" fill="url(#g6)" />
    <ellipse id="glow-7" cx="490" cy="230" rx="220" ry="170" fill="url(#g7)" />
    <ellipse id="glow-8" cx="590" cy="250" rx="150" ry="130" fill="url(#g8)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #A855F7, #6D28D9)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <img src={github?.user?.avatarUrl ?? 'https://github.com/tchindjiarufina.png'} width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8, zIndex: 10 }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      {'Rufina'}
    </div>
    <div style={{ display:'flex', fontSize:15, color:'rgba(196,181,253,0.9)', fontWeight:400, letterSpacing:'0.3px' }}>
      {'Developer in training • Systems Development • Cybersecurity'}
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6, flexWrap: 'wrap' }}>
      {['JavaScript', 'HTML', 'CSS', 'Git'].map((tag, i) => {
        return (
          <div key={tag + '-' + i} style={{
            display:'flex', padding:'4px 12px', borderRadius:20,
          background:'rgba(168,85,247,0.15)',
          border:'1px solid rgba(168,85,247,0.35)',
          color:'rgba(221,214,254,0.95)', fontSize:12, fontWeight:600,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

```aura width=860 height=22 link="https://collectioneur.github.io/readme-aura/"
  <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', width: '100%', height: '100%', padding: 0, margin: 0 }}>
    <span style={{ fontSize: 12, lineHeight: 1, color: 'rgba(150,140,200,0.55)', fontWeight: 500, letterSpacing: '0.4px' }}>powered by readme-aura</span>
  </div>
```
```aura width=860 height=120
<div style={{
  width: '100%',
  height: '100%',
  background: '#08050F',
  display: 'flex',
  alignItems: 'center',
  justifyContent: 'center',
  flexWrap: 'wrap',
  gap: 12,
  padding: 15
}}>

 <img src="https://skillicons.dev/icons?i=js,html,css,git,github,azure,linux,arduino,figma,vscode,trello" height={45} />
</div>
```
```aura width=860 height=150
<div style={{
  width: '100%',
  height: '100%',
  background: '#08050F',
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'center',
  padding: '0 40px',
  boxSizing: 'border-box'
}}>
  <div style={{
    display: 'flex',
    fontSize: 24,
    fontWeight: 800,
    color: '#C4B5FD',
    marginBottom: 12
  }}>
    About Me
  </div>

  <div style={{
    display: 'flex',
    fontSize: 15,
    lineHeight: 1.6,
    color: 'rgba(221,214,254,0.85)'
  }}>
    I'm Rufina, a Systems Development student passionate about technology and software development. I'm currently building my skills through hands-on projects and exploring my interest in cybersecurity.
  </div>
</div>
```

```aura width=860 height=70
<div style={{
  width: '100%',
  height: '100%',
  background: '#08050F',
  display: 'flex',
  alignItems: 'center',
  padding: '0 40px',
  boxSizing: 'border-box',
  borderBottom: '1px solid rgba(168,85,247,0.20)'
}}>
  <div style={{
    display: 'flex',
    fontSize: 22,
    fontWeight: 800,
    color: '#FFFFFF',
    letterSpacing: '0.5px'
  }}>
    Tech Stack
  </div>

  <div style={{
    display: 'flex',
    marginLeft: 12,
    fontSize: 14,
    color: '#A855F7'
  }}>
    // tools & technologies
  </div>
</div>
```
  
```
```aura width=860 height=190
<div style={{
  width: '100%',
  height: '100%',
  background: '#08050F',
  display: 'flex',
  flexDirection: 'column',
  alignItems: 'center',
  justifyContent: 'center',
  padding: '18px 30px',
  boxSizing: 'border-box'
}}>

  <div style={{
    display: 'flex',
    fontSize: 13,
    fontWeight: 700,
    color: '#C4B5FD',
    letterSpacing: '2px',
    marginBottom: 14
  }}>
    TECHNOLOGIES & TOOLS
  </div>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    justifyContent: 'center',
    padding: '12px 22px',
    borderRadius: 16,
    background: 'rgba(168,85,247,0.07)',
    border: '1px solid rgba(168,85,247,0.22)',
    boxShadow: '0 0 30px rgba(168,85,247,0.08)'
  }}>
    <img
      src="https://skillicons.dev/icons?i=js,html,css,git,github,azure,linux,arduino,figma,vscode,trello"
      height={45}
    />
  </div>

  <div style={{
    display: 'flex',
    marginTop: 14,
    gap: 10,
    alignItems: 'center'
  }}>
    <span style={{
      fontSize: 12,
      color: 'rgba(196,181,253,0.65)',
      fontWeight: 500
    }}>
      PuTTY
    </span>

    <span style={{
      fontSize: 12,
      color: 'rgba(168,85,247,0.45)'
    }}>
      •
    </span>

    <span style={{
      fontSize: 12,
      color: 'rgba(196,181,253,0.65)',
      fontWeight: 500
    }}>
      MQTT
    </span>
  </div>

</div>
```
```aura width=860 height=80
<div style={{
  width: '100%',
  height: '100%',
  background: '#08050F',
  display: 'flex',
  alignItems: 'center',
  justifyContent: 'center'
}}>
  <a
    href="https://www.linkedin.com/in/tchindjia-g-0a6563366/"
    style={{
      display: 'flex',
      alignItems: 'center',
      gap: 10,
      padding: '10px 22px',
      borderRadius: 12,
      background: 'rgba(168,85,247,0.10)',
      border: '1px solid rgba(168,85,247,0.25)',
      color: '#C4B5FD',
      fontSize: 14,
      fontWeight: 700,
      textDecoration: 'none'
    }}
  >
    LinkedIn
  </a>
</div>
```