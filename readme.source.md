```aura width=800 height=380 link="https://github.com/Rehxn2k06"
<div style={{position:'relative',display:'flex',flexDirection:'column',width:'100%',height:'100%',background:'#080808',overflow:'hidden',fontFamily:'Inter, sans-serif'}}>
  <style>{`
    @keyframes scan{0%{transform:translateY(0px);opacity:0}8%{opacity:.6}92%{opacity:.2}100%{transform:translateY(381px);opacity:0}}
    @keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
    @keyframes pdot{0%,100%{opacity:.2}50%{opacity:1}}
    @keyframes gfade{0%,100%{opacity:.04}50%{opacity:.13}}
    #sl{animation:scan 8s linear infinite}
    #cur{animation:blink 1.2s step-end infinite}
    #dot{animation:pdot 2.5s ease-in-out infinite}
    #ga{animation:gfade 10s ease-in-out infinite}
    #gb{animation:gfade 14s ease-in-out infinite 3s}
  `}</style>

  <div id="ga" style={{position:'absolute',top:-100,right:-100,width:420,height:420,borderRadius:'50%',background:'radial-gradient(circle,rgba(103,232,249,.22) 0%,transparent 65%)'}}/>
  <div id="gb" style={{position:'absolute',bottom:-120,left:-80,width:340,height:340,borderRadius:'50%',background:'radial-gradient(circle,rgba(103,232,249,.13) 0%,transparent 65%)'}}/>

  <div id="sl" style={{position:'absolute',left:0,right:0,height:1,background:'linear-gradient(90deg,transparent,rgba(103,232,249,.5) 35%,rgba(103,232,249,.85) 50%,rgba(103,232,249,.5) 65%,transparent)'}}/>

  <div style={{position:'absolute',top:18,left:18,width:14,height:14,borderTop:'1.5px solid rgba(103,232,249,.5)',borderLeft:'1.5px solid rgba(103,232,249,.5)'}}/>
  <div style={{position:'absolute',top:18,right:18,width:14,height:14,borderTop:'1.5px solid rgba(103,232,249,.5)',borderRight:'1.5px solid rgba(103,232,249,.5)'}}/>
  <div style={{position:'absolute',bottom:18,left:18,width:14,height:14,borderBottom:'1.5px solid rgba(103,232,249,.5)',borderLeft:'1.5px solid rgba(103,232,249,.5)'}}/>
  <div style={{position:'absolute',bottom:18,right:18,width:14,height:14,borderBottom:'1.5px solid rgba(103,232,249,.5)',borderRight:'1.5px solid rgba(103,232,249,.5)'}}/>

  <div style={{position:'absolute',top:26,right:44,display:'flex',alignItems:'center',gap:7}}>
    <div id="dot" style={{width:5,height:5,borderRadius:'50%',background:'#67E8F9'}}/>
    <div style={{color:'rgba(103,232,249,.55)',fontSize:9,letterSpacing:2.5}}>STATUS: ACTIVE</div>
  </div>

  <div style={{display:'flex',flexDirection:'column',justifyContent:'center',height:'100%',padding:'0 56px'}}>
    <div style={{color:'rgba(103,232,249,.55)',fontSize:10,letterSpacing:4,marginBottom:18}}>REHAN IMTIYAJ MULLA  ·  ML ENGINEER</div>
    <div style={{color:'#FFFFFF',fontSize:68,fontWeight:800,letterSpacing:-2,lineHeight:1,marginBottom:2}}>Building</div>
    <div style={{display:'flex',alignItems:'baseline',marginBottom:26}}>
      <div style={{color:'#FFFFFF',fontSize:68,fontWeight:800,letterSpacing:-2,lineHeight:1}}>Intelligence</div>
      <div id="cur" style={{color:'#67E8F9',fontSize:68,fontWeight:300,lineHeight:1,marginLeft:4}}>_</div>
    </div>
    <div style={{color:'rgba(255,255,255,.4)',fontSize:13.5,lineHeight:1.65}}>
      CSE + Data Science @ DSCE, Bengaluru  ·  Reliance Foundation Scholar 24  ·  Targeting quant / ML research
    </div>
  </div>

  <div style={{position:'absolute',bottom:26,left:56,display:'flex',gap:40}}>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>LOCATION</div>
      <div style={{color:'rgba(255,255,255,.5)',fontSize:10,letterSpacing:.5}}>BENGALURU, IN</div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>CGPA</div>
      <div style={{color:'rgba(255,255,255,.5)',fontSize:10,letterSpacing:.5}}>9.0 / 10.0</div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>GRAD</div>
      <div style={{color:'rgba(255,255,255,.5)',fontSize:10,letterSpacing:.5}}>2028</div>
    </div>
    <div style={{display:'flex',flexDirection:'column',gap:3}}>
      <div style={{color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2}}>SCHOLAR</div>
      <div style={{color:'#67E8F9',fontSize:10,letterSpacing:.5}}>RELIANCE FOUNDATION 24</div>
    </div>
  </div>
</div>
```

```aura width=800 height=310
<div style={{position:'relative',display:'flex',flexDirection:'column',width:'100%',height:'100%',background:'#080808',fontFamily:'Inter, sans-serif',padding:'28px 24px 24px'}}>
  <div style={{color:'rgba(103,232,249,.55)',fontSize:9,letterSpacing:3,marginBottom:18}}>FEATURED PROJECTS</div>
  <div style={{display:'flex',gap:14,flex:1}}>

    <div style={{position:'relative',display:'flex',flexDirection:'column',flex:1,border:'1px solid rgba(255,255,255,.07)',padding:'18px',gap:8}}>
      <div style={{position:'absolute',top:-1,left:-1,width:10,height:10,borderTop:'1.5px solid rgba(103,232,249,.7)',borderLeft:'1.5px solid rgba(103,232,249,.7)'}}/>
      <div style={{color:'rgba(255,255,255,.2)',fontSize:8,letterSpacing:2,marginBottom:2}}>01 / CURA</div>
      <div style={{color:'#FFFFFF',fontSize:15,fontWeight:700,lineHeight:1.25}}>ICU Deterioration Predictor</div>
      <div style={{color:'rgba(255,255,255,.38)',fontSize:10.5,lineHeight:1.55}}>Isolation Forest + LSTM pipeline for early patient deterioration detection. Dockerized, production-grade.</div>
      <div style={{color:'#67E8F9',fontSize:10,fontWeight:600,marginTop:'auto'}}>94.1% acc  ·  100% recall</div>
      <div style={{display:'flex',gap:6,marginTop:6}}>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>LSTM</div>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>IsolationForest</div>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Docker</div>
      </div>
    </div>

    <div style={{position:'relative',display:'flex',flexDirection:'column',flex:1,border:'1px solid rgba(255,255,255,.07)',padding:'18px',gap:8}}>
      <div style={{position:'absolute',top:-1,left:-1,width:10,height:10,borderTop:'1.5px solid rgba(103,232,249,.7)',borderLeft:'1.5px solid rgba(103,232,249,.7)'}}/>
      <div style={{color:'rgba(255,255,255,.2)',fontSize:8,letterSpacing:2,marginBottom:2}}>02 / AEGIS</div>
      <div style={{color:'#FFFFFF',fontSize:15,fontWeight:700,lineHeight:1.25}}>LLM Robustness Framework</div>
      <div style={{color:'rgba(255,255,255,.38)',fontSize:10.5,lineHeight:1.55}}>Adversarial prompt hardening and robustness testing for large language models under distribution shift.</div>
      <div style={{color:'#67E8F9',fontSize:10,fontWeight:600,marginTop:'auto'}}>~40% token reduction</div>
      <div style={{display:'flex',gap:6,marginTop:6}}>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>LLMs</div>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>NLP</div>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Python</div>
      </div>
    </div>

    <div style={{position:'relative',display:'flex',flexDirection:'column',flex:1,border:'1px solid rgba(255,255,255,.07)',padding:'18px',gap:8}}>
      <div style={{position:'absolute',top:-1,left:-1,width:10,height:10,borderTop:'1.5px solid rgba(103,232,249,.7)',borderLeft:'1.5px solid rgba(103,232,249,.7)'}}/>
      <div style={{color:'rgba(255,255,255,.2)',fontSize:8,letterSpacing:2,marginBottom:2}}>03 / AUXESIS</div>
      <div style={{color:'#FFFFFF',fontSize:15,fontWeight:700,lineHeight:1.25}}>Compiler Flag Recommender</div>
      <div style={{color:'rgba(255,255,255,.38)',fontSize:10.5,lineHeight:1.55}}>Surrogate XGBoost model predicting compiler runtime from static code features via LOO cross-validation.</div>
      <div style={{color:'#67E8F9',fontSize:10,fontWeight:600,marginTop:'auto'}}>R²=0.91  ·  RMSE=0.029s</div>
      <div style={{display:'flex',gap:6,marginTop:6}}>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>XGBoost</div>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Surrogate</div>
        <div style={{color:'rgba(255,255,255,.28)',fontSize:9,border:'1px solid rgba(255,255,255,.1)',padding:'2px 7px'}}>Python</div>
      </div>
    </div>

  </div>
</div>
```

```aura width=800 height=175
<div style={{display:'flex',flexDirection:'column',width:'100%',height:'100%',background:'#080808',fontFamily:'Inter, sans-serif',padding:'28px 56px 24px'}}>
  <div style={{color:'rgba(103,232,249,.55)',fontSize:9,letterSpacing:3,marginBottom:20}}>CURRENTLY BUILDING</div>
  <div style={{display:'flex',gap:48}}>

    <div style={{display:'flex',flexDirection:'column',gap:12,flex:1}}>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Karpathy Zero to Hero</div>
          <div style={{color:'rgba(255,255,255,.32)',fontSize:10}}>Past micrograd  →  makemore / MLP  →  transformer</div>
        </div>
      </div>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Fast.ai Practical DL  (parallel)</div>
          <div style={{color:'rgba(255,255,255,.32)',fontSize:10}}>Building end-to-end intuition alongside theory</div>
        </div>
      </div>
    </div>

    <div style={{display:'flex',flexDirection:'column',gap:12,flex:1}}>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Research Co-authorship @ DSCE</div>
          <div style={{color:'rgba(255,255,255,.32)',fontSize:10}}>Professor outreach  ·  concept drift domain</div>
        </div>
      </div>
      <div style={{display:'flex',gap:10,alignItems:'flex-start'}}>
        <div style={{color:'#67E8F9',fontSize:10,marginTop:1}}>▸</div>
        <div style={{display:'flex',flexDirection:'column',gap:2}}>
          <div style={{color:'rgba(255,255,255,.82)',fontSize:11,fontWeight:600}}>Targets: EleutherAI SOAR  ·  Cohere  ·  IMI</div>
          <div style={{color:'rgba(255,255,255,.32)',fontSize:10}}>Open research fellowships  ·  Aug & Oct 2026</div>
        </div>
      </div>
    </div>

  </div>
</div>
```

```aura width=800 height=80
<div style={{display:'flex',alignItems:'center',width:'100%',height:'100%',background:'#080808',fontFamily:'Inter, sans-serif',padding:'0 56px',gap:0}}>
  <div style={{color:'rgba(255,255,255,.18)',fontSize:8,letterSpacing:2.5,marginRight:28}}>TECH STACK</div>
  <div style={{display:'flex',gap:8}}>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Python</div>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>PyTorch</div>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>NumPy</div>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>XGBoost</div>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Scikit-Learn</div>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Docker</div>
    <div style={{color:'rgba(255,255,255,.48)',fontSize:10,border:'1px solid rgba(255,255,255,.1)',padding:'4px 10px'}}>Git</div>
  </div>
</div>
```

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rehxn2k06&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&bg_color=080808&title_color=67E8F9&icon_color=67E8F9" height="160"/>
  &nbsp;&nbsp;
  <img src="https://streak-stats.demolab.com?user=Rehxn2k06&theme=tokyonight&hide_border=true&background=080808&ring=67E8F9&fire=67E8F9&currStreakLabel=67E8F9" height="160"/>
</p>

```aura width=150 height=44 link="https://www.linkedin.com/in/rehan-mulla-8719b62b8/" inline align=center
<div style={{display:'flex',alignItems:'center',justifyContent:'center',width:'100%',height:'100%',background:'#080808',border:'1px solid rgba(103,232,249,.3)',fontFamily:'Inter, sans-serif',gap:8}}>
  <div style={{color:'#67E8F9',fontSize:11,letterSpacing:1.5}}>LINKEDIN</div>
</div>
```
```aura width=150 height=44 link="https://github.com/Rehxn2k06" inline align=center
<div style={{display:'flex',alignItems:'center',justifyContent:'center',width:'100%',height:'100%',background:'#080808',border:'1px solid rgba(103,232,249,.3)',fontFamily:'Inter, sans-serif',gap:8}}>
  <div style={{color:'#67E8F9',fontSize:11,letterSpacing:1.5}}>GITHUB</div>
</div>
```
```aura width=150 height=44 link="mailto:rehxn5762@gmail.com" inline align=center
<div style={{display:'flex',alignItems:'center',justifyContent:'center',width:'100%',height:'100%',background:'#080808',border:'1px solid rgba(103,232,249,.3)',fontFamily:'Inter, sans-serif',gap:8}}>
  <div style={{color:'#67E8F9',fontSize:11,letterSpacing:1.5}}>EMAIL</div>
</div>
```