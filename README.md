# 面試作業／陌生 Repo 防詐檢查表  
# Interview / Unfamiliar Repo Safety Checklist

Some “coding tests” or “take‑home assignments” can be scams or malware.  
有些「面試作業」「技術測驗」，其實是在騙你點連結、登入、或執行壞程式。

This checklist is for junior devs and “小學生程式設計師”.  
這份檢查表，用最簡單的規則保護你。

> If you don’t understand it, **stop** and ask.  
> 看不懂、想不通、說不清，就先停下來，先問人再做。

---

## 0. 3 大原則（3 Main Rules）

1. **No email button for login or payment.**  
   不用信裡的按鈕登入或付款，只用自己打的官網。 

2. **No running code you don’t understand.**  
   不執行看不懂、說不清用途的檔案或指令。 

3. **New repo in VS Code → Trust = No.**  
   VS Code 問「Do you trust the authors?」一律先選 **No**。 

If you only remember these 3, you already removed many attacks.  
只記得這 3 點，就已經擋掉很多攻擊。

---

## 1. 看「人」和「訊息」  
## Check the Sender & Message

- 中文：
  - [ ] 突然加你、薪水好到不合理、一直催你快決定 → 小心。
  - [ ] 公司／專案名字，用 Google 找得到官網和真實員工。 
- English:
  - [ ] “Too good to be true” offers (very high pay, very urgent) → be careful.
  - [ ] You can find the company and people on official sites / LinkedIn.

---

## 2. 看「信件」和「私訊」  
## Check Email & DM

- 中文：
  - [ ] 不在信裡直接點「登入」「付款」「下載」按鈕。自己開官方網站或 App。 
  - [ ] 看寄件人信箱 `@` 後面，是不是公司網域（例如 `@company.com`）。  
- English:
  - [ ] Don’t click login / payment / download buttons in emails. Go to the official site yourself.
  - [ ] Check the part after `@`. Is it a real company domain (like `@company.com`)?

---

## 3. 看「連結」  
## Check Links

- 中文：
  - [ ] 滑鼠移到連結上，看網址：拼字怪、多一個字、一堆亂數 → 危險。 
  - [ ] 不點陌生人丟來的短網址。  
- English:
  - [ ] Hover the link. Weird spelling, extra letters, or random numbers = danger.
  - [ ] Avoid random short links from strangers.

---

## 4. 看「檔案」和「Repo」  
## Check Files & Repos

- 中文：
  - [ ] 陌生人給的 `.zip`、`.exe`、`.bat`、`.js`、`.ps1` 不隨便打開或執行。  
  - [ ] 面試作業的 repo：先看 README，題目內容要簡單清楚，不應該是一個超大型專案。 
  - [ ] 打開前先看 `.vscode/`、`package.json`、`tasks.json` 等，有沒有「自動下載或執行腳本」的設定。 
- English:
  - [ ] Don’t run `.exe`, `.bat`, `.js`, `.ps1` from strangers.
  - [ ] For interview repos, read the README first. The task should be small and clear, not a huge system.
  - [ ] Before running anything, inspect `.vscode/` and scripts for auto‑download / auto‑run logic.

---

## 5. VS Code Workspace Trust（新專案一律先 No）  
## VS Code Workspace Trust (Always No First)

- 中文：
  - [ ] 開陌生專案時，VS Code 問「Do you trust the authors?」→ 先選 **No**，只先看檔案內容。 
  - [ ] 不直接安裝專案推薦的 extension，先看作者是誰、做什麼。  
- English:
  - [ ] New repo → when VS Code asks “Do you trust the authors?”, click **No** first.
  - [ ] Don’t auto‑install recommended extensions. Check who made them and why.

---

## 6. 用 AI 再看一眼（30 秒版）  
## 30‑Second AI Safety Check

每次收到「面試作業 repo／奇怪信件／不熟網站」，可以先丟給 AI：  

**Prompt 模板（直接複製貼上）：**

> You are a security reviewer.  
> 你是一名資安老師。  
> 1. Please read this email / chat / job description.  
>    幫我列出裡面所有可能是詐騙或釣魚的紅旗。  
> 2. Please scan this URL / page / repo.  
>    幫我找：  
>    - 要我馬上登入、付款、交出密碼或驗證碼的地方  
>    - 會自動下載或執行程式碼的 script 或設定  
> 3. Give me a risk level: Low / Medium / High, and one sentence of advice to continue or stop.  
>    請給我風險等級（Low / Medium / High），再用一句話建議「繼續」還是「停止」。

使用規則：  

- AI 說 **High** → 直接停，不做。  
- AI 說 **Medium** → 你要非常小心，只在真的必要時才考慮繼續。  
- AI 說 **Low** → 還是要遵守上面的 3 大原則和各項檢查。 

> AI 是放大鏡，不是保險箱。  
> AI 覺得怪，你一定要慢一拍；AI 覺得還好，你也要自己再想一想。

---

## 7. 已經點了怎麼辦？  
## What If You Already Clicked / Ran It?

- 中文：
  - 立刻：關掉網頁或程式 → 先斷網 → 改所有重要帳號的密碼 → 開啟或確認 2FA／MFA。 
  - 告訴信任的大人、同事或資安窗口，不要自己悶著不講。  
- English:
  - Immediately: close the page or app → disconnect from the internet → change important passwords → enable 2FA/MFA.
  - Tell a trusted person or security team. Don’t hide it.

---

## 一頁版總結（給國小程式設計師）

- 不急：不要因為對方說「很趕」就亂按。  
- 不貪：太好的薪水或獎品，多半有問題。  
- 不怕問：不懂就問大人／同事／AI，再決定要不要點。  

> 看到怪怪的東西，**先問再點**。  
