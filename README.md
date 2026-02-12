![Header](https://capsule-render.vercel.app/api?type=cylinder&color=0:1a1a2e,40:16213E,70:2C3E50,100:34495E&height=200&section=header&text=Welcome%20Here%20🌌&fontSize=70&animation=twinkling&desc=There's%20a%20reason%20you%20found%20me%20in%20this%20vast%20universe&descAlignY=75&fontColor=E0E0E0)

<div style="margin: 40px 0">

### `{ Owen }` 
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=500&duration=2000&color=7A28F7&random=false&width=435&lines=System+Architect+Design;Mensa+Member;AI/SW+Engineer;Human)

> Hi, I'm Owen from Taiwan.  
>  
> After years of coding journey,  
> I made a bold decision to embrace a gap year,  
> starting from late 2024.  
>   
> Since then, I've adopted a more fluid way of working and thinking,
> focusing on building my own solutions,  
> and turning ideas into reality.  

<div style="margin: 40px 0">

### 💭 Philosophy

<div style="padding: 20px; border-radius: 8px; background-color: #1a1a2e; color: #E0E0E0">

> In an era where everyone chases titles and wealth,  
> we're always busy planning for tomorrow,  
> missing the precious moments of today.  
>   
> True happiness isn't found in final achievements,  
> but in every surprise and growth along the way.  

</div>
</div>

### 🎯 Field I Experenced

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#0f172a',
      'primaryTextColor': '#f8fafc',
      'primaryBorderColor': '#334155',
      'lineColor': '#475569',
      'fontFamily': 'monospace',
      'fontSize': '13px'
    }
  }
}%%

graph LR
    %% ==========================================
    %% 1. 定義節點 (內容完全收錄)
    %% ==========================================

    %% --- Central Node ---
    Root((Technical<br/>Journey))

    %% ================= LEFT SIDE (Hard/Math) =================
    %% 技巧：全部指向 Root (Node --> Root) 讓它們排在左邊

    %% --- Mathematical Foundations (Red) ---
    Math(Mathematical<br/>Foundations) === Root
    
    M_Opt[Optimization Theory] --- Math
    M_Opt --- M_Lin[Linear Prog]
    M_Opt --- M_Non[Nonlinear Prog]
    
    M_Stat[Statistical Analysis] --- Math
    M_Stat --- M_Reg[Regression Models]
    M_Stat --- M_TS[Time Series Analysis]

    %% --- Industrial Systems (Teal) ---
    Ind(Industrial<br/>Systems) === Root
    
    I_Auto[Automation Control] --- Ind
    I_Auto --- I_PLC[PLC Programming]
    I_Auto --- I_Mot[Motion Control]
    I_Auto --- I_Sen[Sensor Integration]

    %% --- IoT (Green) ---
    IoT(IoT &<br/>Edge) === Root
    
    I_Data[Data Acquisition] --- IoT
    I_RT[Real-time Monitor] --- IoT

    %% ================= RIGHT SIDE (Soft/AI) =================
    %% 技巧：Root 指向它們 (Root --> Node) 讓它們排在右邊

    %% --- AI & Analytics (Purple) ---
    Root === AI(AI &<br/>Analytics)
    
    AI --- CV[Computer Vision]
    CV --- CV_OCR[OCR Development]
    CV --- CV_CBIR[CBIR Systems]
    CV --- CV_Obj[Object Tracing]
    CV --- CV_Seg[Image Segmentation]

    AI --- ML[Machine Learning]
    ML --- ML_Sup[Supervised]
    ML_Sup --- ML_Class[Classification]
    ML_Sup --- ML_Regr[Regression]
    
    ML --- ML_Unsup[Unsupervised]
    ML_Unsup --- ML_Clus[Clustering]
    ML_Unsup --- ML_Dim[Dim Reduction]
    
    ML --- ML_App[Applications]
    ML_App --- ML_Ano[Anomaly Detect]
    ML_App --- ML_Pat[Pattern Recog]
    ML_App --- ML_Pre[Predictive Models]

    %% --- Software Systems (Blue) ---
    Root === SW(Software<br/>Systems)
    
    SW --- BE[Backend Arch]
    BE --- B_Rest[RESTful APIs]
    BE --- B_Micro[Microservices]
    BE --- B_MQ[Message Queues]
    
    SW --- DB[Database]
    DB --- D_SQL[SQL/NoSQL]
    DB --- D_TS[Time Series DB]
    
    SW --- FE[Frontend]
    FE --- F_Re[React / Next.js]
    FE --- F_WS[WebSocket]

    %% --- DevOps (Orange) ---
    Root === Ops(DevOps<br/>& Infra)
    
    Ops --- Cont[Container Orchestration]
    Cont --- O_Dock[Docker]
    Cont --- O_K8s[Kubernetes]
    
    Ops --- CI[CI / CD Solutions]
    CI --- O_Jen[Jenkins]
    CI --- O_GH[GitHub Actions]

    %% ==========================================
    %% 2. 樣式定義 (ClassDef) - 100% 可控色
    %% ==========================================

    classDef root fill:#0f172a,stroke:#e2e8f0,stroke-width:4px,color:#fff,font-weight:bold,font-size:16px;

    %% 數學 (Math) - 深紅
    classDef math fill:#881337,stroke:#fb7185,stroke-width:2px,color:#fff;
    classDef math_sub fill:#4c0519,stroke:#fb7185,stroke-width:1px,color:#ffe4e6;

    %% 工控 (Industrial) - 深青
    classDef ind fill:#134e4a,stroke:#2dd4bf,stroke-width:2px,color:#fff;
    classDef ind_sub fill:#11282b,stroke:#2dd4bf,stroke-width:1px,color:#ccfbf1;

    %% IoT - 深綠
    classDef iot fill:#065f46,stroke:#34d399,stroke-width:2px,color:#fff;
    classDef iot_sub fill:#022c22,stroke:#34d399,stroke-width:1px,color:#d1fae5;

    %% AI - 深紫
    classDef ai fill:#581c87,stroke:#a855f7,stroke-width:2px,color:#fff;
    classDef ai_sub fill:#241b35,stroke:#a855f7,stroke-width:1px,color:#f3e8ff;

    %% Software - 深藍
    classDef sw fill:#1e3a8a,stroke:#60a5fa,stroke-width:2px,color:#fff;
    classDef sw_sub fill:#172554,stroke:#60a5fa,stroke-width:1px,color:#dbeafe;

    %% DevOps - 深橘褐
    classDef ops fill:#7c2d12,stroke:#fb923c,stroke-width:2px,color:#fff;
    classDef ops_sub fill:#431407,stroke:#fb923c,stroke-width:1px,color:#ffedd5;

    %% ==========================================
    %% 3. 套用樣式
    %% ==========================================
    
    class Root root;

    class Math math;
    class M_Opt,M_Lin,M_Non,M_Stat,M_Reg,M_TS math_sub;

    class Ind ind;
    class I_Auto,I_PLC,I_Mot,I_Sen ind_sub;

    class IoT iot;
    class I_Data,I_RT iot_sub;

    class AI ai;
    class CV,CV_OCR,CV_CBIR,CV_Obj,CV_Seg,ML,ML_Sup,ML_Class,ML_Regr,ML_Unsup,ML_Clus,ML_Dim,ML_App,ML_Ano,ML_Pat,ML_Pre ai_sub;

    class SW sw;
    class BE,B_Rest,B_Micro,B_MQ,DB,D_SQL,D_TS,FE,F_Re,F_WS sw_sub;

    class Ops ops;
    class Cont,O_Dock,O_K8s,CI,O_Jen,O_GH ops_sub;
```

</div> <div style="margin: 30px 0">
📫 Connect me: wei-chien.hsiao.tw@member.mensa.org

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,40:16213E,70:2C3E50,100:34495E&height=100&section=footer)
