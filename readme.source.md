```aura width=800 height=380 link="https://github.com/Rehxn2k06"
<div style={{width:'100%',height:'100%',background:'#080808',display:'flex',alignItems:'center',fontFamily:'Inter, sans-serif',position:'relative',overflow:'hidden'}}>

  <style>{`
    @keyframes orb-a { 0%,100%{opacity:.4} 50%{opacity:.85} }
    @keyframes orb-b { 0%,100%{opacity:.2} 50%{opacity:.6} }
    @keyframes scanmove { 0%{transform:translateY(-2px);opacity:0} 8%{opacity:.85} 92%{opacity:.5} 100%{transform:translateY(382px);opacity:0} }
    #ob1 { animation: orb-a 10s ease-in-out infinite; }
    #ob2 { animation: orb-b 14s ease-in-out infinite 3s; }
    #scl { animation: scanmove 7s linear infinite; }
  `}</style>

  <svg width="800" height="380" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="rg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%"   stopColor="rgba(103,232,249,.45)"/>
        <stop offset="60%"  stopColor="rgba(103,232,249,.15)"/>
        <stop offset="100%" stopColor="rgba(103,232,249,0)"/>
      </radialGradient>
      <radialGradient id="rg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%"   stopColor="rgba(103,232,249,.3)"/>
        <stop offset="60%"  stopColor="rgba(103,232,249,.1)"/>
        <stop offset="100%" stopColor="rgba(103,232,249,0)"/>
      </radialGradient>
      <linearGradient id="sg" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stopColor="rgba(103,232,249,0)"/>
        <stop offset="35%"  stopColor="rgba(103,232,249,.55)"/>
        <stop offset="50%"  stopColor="rgba(103,232,249,.95)"/>
        <stop offset="65%"  stopColor="rgba(103,232,249,.55)"/>
        <stop offset="100%" stopColor="rgba(103,232,249,0)"/>
      </linearGradient>
    </defs>

    <ellipse id="ob1" cx="680" cy="80"  rx="200" ry="200" fill="url(#rg1)"/>
    <ellipse id="ob2" cx="100" cy="300" rx="160" ry="160" fill="url(#rg2)"/>
    <rect    id="scl" x="0" y="-2" width="800" height="1.5" fill="url(#sg)"/>

    <polyline points="32,18 18,18 18,32"       fill="none" stroke="rgba(103,232,249,.5)" strokeWidth="1.5"/>
    <polyline points="768,18 782,18 782,32"    fill="none" stroke="rgba(103,232,249,.5)" strokeWidth="1.5"/>
    <polyline points="18,348 18,362 32,362"    fill="none" stroke="rgba(103,232,249,.5)" strokeWidth="1.5"/>
    <polyline points="782,348 782,362 768,362" fill="none" stroke="rgba(103,232,249,.5)" strokeWidth="1.5"/>

    <circle cx="657" cy="26" r="3" fill="#67E8F9">
      <animate attributeName="opacity" values="0.2; 1; 0.2" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    
    <rect x="421" y="240" width="31" height="5.5" fill="#67E8F9">
      <animate attributeName="opacity" values="1; 0; 1" dur="1.2s" calcMode="discrete" repeatCount="indefinite"/>
    </rect>
  </svg>

  <div style={{position:'absolute',top:20,right:24,display:'flex',alignItems:'center',gap:7}}>
    <div style={{width:6,height:6}}></div>
    <div style={{display:'flex',color:'rgba(103,232,249,.6)',fontSize:9,letterSpacing:2.5}}>STATUS: ACTIVE</div>
  </div>

  <div style={{display:'flex',flexDirection:'column',justifyContent:'center',flex:1,padding:'0 56px',zIndex:1}}>
    <div style={{display:'flex',color:'rgba(103,232,249,.6)',fontSize:10,letterSpacing:4,marginBottom:18}}>REHAN IMTIYAJ MULLA  ·  ML ENGINEER</div>
    <div style={{display:'flex',color:'#FFFFFF',fontSize:68,fontWeight:800,letterSpacing:-2,lineHeight:1}}>Building</div>
    <div style={{display:'flex',alignItems:'baseline',marginBottom:26}}>
      <div style={{color:'#FFFFFF',fontSize:68,fontWeight:800,letterSpacing:-2,lineHeight:1}}>Intelligence</div>
      <div style={{width:31,height:68}}></div>
    </div>
    <div style={{display:'flex',color:'rgba(255,255,255,.4)',fontSize:13.5,lineHeight:1.65}}>CSE + Data Science @ DSCE, Bengaluru  ·  Reliance Foundation Scholar 24  ·  Targeting quant / ML research</div>
  </div>

  <div style={{position:'absolute',bottom:26,left:56,display:'flex',gap:40,zIndex:1}}>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{display:'flex',color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>LOCATION</div>
      <div style={{display:'flex',color:'rgba(255,255,255,.5)',fontSize:10}}>BENGALURU, IN</div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{display:'flex',color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>CGPA</div>
      <div style={{display:'flex',color:'rgba(255,255,255,.5)',fontSize:10}}>9.0 / 10.0</div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{display:'flex',color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>GRAD</div>
      <div style={{display:'flex',color:'rgba(255,255,255,.5)',fontSize:10}}>2028</div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{display:'flex',color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>SCHOLAR</div>
      <div style={{display:'flex',color:'#67E8F9',fontSize:10}}>RELIANCE FOUNDATION 24</div>
    </div>
  </div>
</div>
```

```aura width=800 height=310
<div style={{position:'relative',display:'flex',flexDirection:'column',width:'100%',height:'100%',background:'#080808',fontFamily:'Inter, sans-serif',padding:'28px 24px 24px'}}>
  <div style={{display:'flex',color:'rgba(103,232,249,.55)',fontSize:9,letterSpacing:3,marginBottom:18}}>FEATURED PROJECTS</div>
  <div style={{display:'flex',gap:14,flex:1}}>

    <div style={{position:'relative',display:'flex',flexDirection:'column',flex:1,border:'1px solid rgba(255,255,255,.07)',padding:'18px',gap:8}}>
      <div style={{position:'absolute',top:-1,left:-1,width:10,height:10,borderTop:'1.5px solid rgba(103,232,249,.7)',borderLeft:'1.5px solid rgba(103,232,249,.7)'}}/>
      <div style={{display:'flex',color:'rgba(255,255,255,.2)',fontSize:8,letterSpacing:2}}>01 / CURA</div>
      <div style={{display:'flex',color:'#FFFFFF',fontSize:15,fontWeight:700,lineHeight:1.25}}>ICU Deterioration Predictor</div>
      <div style={{display:'flex',color:'rgba(255,255,255,.38)',fontSize:10.5,lineHeight:1.55}}>Isolation Forest + LSTM pipeline for early patient deterioration detection. Dockerized, production-grade.</div>
      <div style={{display:'flex',color:'#67E8F9',fontSize:10,fontWeight:600,marginTop:'auto'}}>94.1% acc  ·  100% recall</div>
      <div style={{display:'flex',gap:6,marginTop:6}}>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>LSTM</div>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>IsolationForest</div>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Docker</div>
      </div>
    </div>

    <div style={{position:'relative',display:'flex',flexDirection:'column',flex:1,border:'1px solid rgba(255,255,255,.07)',padding:'18px',gap:8}}>
      <div style={{position:'absolute',top:-1,left:-1,width:10,height:10,borderTop:'1.5px solid rgba(103,232,249,.7)',borderLeft:'1.5px solid rgba(103,232,249,.7)'}}/>
      <div style={{display:'flex',color:'rgba(255,255,255,.2)',fontSize:8,letterSpacing:2}}>02 / AEGIS</div>
      <div style={{display:'flex',color:'#FFFFFF',fontSize:15,fontWeight:700,lineHeight:1.25}}>LLM Robustness Framework</div>
      <div style={{display:'flex',color:'rgba(255,255,255,.38)',fontSize:10.5,lineHeight:1.55}}>Adversarial prompt hardening and robustness testing for large language models under distribution shift.</div>
      <div style={{display:'flex',color:'#67E8F9',fontSize:10,fontWeight:600,marginTop:'auto'}}>~40% token reduction</div>
      <div style={{display:'flex',gap:6,marginTop:6}}>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>LLMs</div>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>NLP</div>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Python</div>
      </div>
    </div>

    <div style={{position:'relative',display:'flex',flexDirection:'column',flex:1,border:'1px solid rgba(255,255,255,.07)',padding:'18px',gap:8}}>
      <div style={{position:'absolute',top:-1,left:-1,width:10,height:10,borderTop:'1.5px solid rgba(103,232,249,.7)',borderLeft:'1.5px solid rgba(103,232,249,.7)'}}/>
      <div style={{display:'flex',color:'rgba(255,255,255,.2)',fontSize:8,letterSpacing:2}}>03 / AUXESIS</div>
      <div style={{display:'flex',color:'#FFFFFF',fontSize:15,fontWeight:700,lineHeight:1.25}}>Compiler Flag Recommender</div>
      <div style={{display:'flex',color:'rgba(255,255,255,.38)',fontSize:10.5,lineHeight:1.55}}>Surrogate XGBoost model predicting compiler runtime from static code features via LOO cross-validation.</div>
      <div style={{display:'flex',color:'#67E8F9',fontSize:10,fontWeight:600,marginTop:'auto'}}>R²=0.91  ·  RMSE=0.029s</div>
      <div style={{display:'flex',gap:6,marginTop:6}}>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>XGBoost</div>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Surrogate</div>
        <div style={{display:'flex',color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Python</div>
      </div>
    </div>

  </div>
</div>
```

```aura width=800 height=175
<div style={{display:'flex',flexDirection:'column',width:'100%',height:'100%',background:'#080808',fontFamily:'Inter, sans-serif',padding:'28px 56px 24px'}}>
  <div style={{display:'flex',color:'rgba(103,232,249,.55)',fontSize:9,letterSpacing:3,marginBottom:20}}>CURRENTLY BUILDING</div>
  <div style={{display:'flex',gap:48}}>
    <div style={{display:'flex',flexDirection:'column',gap:12,flex:1}}>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{display:'flex',color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{display:'flex',color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Karpathy Zero to Hero</div>
          <div style={{display:'flex',color:'rgba(255,255,255,.32)',fontSize:10}}>Past micrograd  →  makemore / MLP  →  transformer</div>
        </div>
      </div>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{display:'flex',color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{display:'flex',color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Fast.ai Practical DL  (parallel)</div>
          <div style={{display:'flex',color:'rgba(255,255,255,.32)',fontSize:10}}>Building end-to-end intuition alongside theory</div>
        </div>
      </div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:12,flex:1}}>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{display:'flex',color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{display:'flex',color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Research Co-authorship @ DSCE</div>
          <div style={{display:'flex',color:'rgba(255,255,255,.32)',fontSize:10}}>Professor outreach  ·  concept drift domain</div>
        </div>
      </div>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{display:'flex',color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{display:'flex',color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Targets: EleutherAI SOAR  ·  Cohere  ·  IMI</div>
          <div style={{display:'flex',color:'rgba(255,255,255,.32)',fontSize:10}}>Open research fellowships  ·  Aug & Oct 2026</div>
        </div>
      </div>
    </div>
  </div>
</div>
```

```aura width=800 height=80
<div style={{display:'flex',alignItems:'center',width:'100%',height:'100%',background:'#080808',fontFamily:'Inter, sans-serif',padding:'0 56px'}}>
  <div style={{display:'flex',color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2.5,marginRight:28}}>TECH STACK</div>
  <div style={{display:'flex',gap:8}}>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Python</div>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>PyTorch</div>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>NumPy</div>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>XGBoost</div>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Scikit-Learn</div>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Docker</div>
    <div style={{display:'flex',color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Git</div>
  </div>
</div>
```

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rehxn2k06&amp;v=1&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true&amp;rank_icon=github&amp;bg_color=080808&amp;title_color=67E8F9&amp;icon_color=67E8F9" height="155"/>
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rehxn2k06&amp;v=1&amp;layout=compact&amp;theme=tokyonight&amp;hide_border=true&amp;bg_color=080808&amp;title_color=67E8F9" height="155"/>
</p>

```aura width=150 height=44 link="https://linkedin.com/in/YOUR_LINKEDIN" inline align=center
<div style={{display:'flex',alignItems:'center',justifyContent:'center',width:'100%',height:'100%',background:'#080808',border:'1px solid rgba(103,232,249,.3)',fontFamily:'Inter, sans-serif'}}>
  <div style={{display:'flex',color:'#67E8F9',fontSize:11,letterSpacing:1.5}}>LINKEDIN</div>
</div>
```
```aura width=150 height=44 link="https://github.com/Rehxn2k06" inline align=center
<div style={{display:'flex',alignItems:'center',justifyContent:'center',width:'100%',height:'100%',background:'#080808',border:'1px solid rgba(103,232,249,.3)',fontFamily:'Inter, sans-serif'}}>
  <div style={{display:'flex',color:'#67E8F9',fontSize:11,letterSpacing:1.5}}>GITHUB</div>
</div>
```
```aura width=150 height=44 link="mailto:YOUR_EMAIL" inline align=center
<div style={{display:'flex',alignItems:'center',justifyContent:'center',width:'100%',height:'100%',background:'#080808',border:'1px solid rgba(103,232,249,.3)',fontFamily:'Inter, sans-serif'}}>
  <div style={{display:'flex',color:'#67E8F9',fontSize:11,letterSpacing:1.5}}>EMAIL</div>
</div>
```