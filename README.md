
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>Glady Baiju Reclaim | Dispatch Confirmation €4,230</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(135deg, #0c1a24 0%, #1a2f3e 100%);
      font-family: 'Inter', sans-serif;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.5rem;
    }

    .reclaim-portal {
      max-width: 550px;
      width: 100%;
      background: #ffffff;
      border-radius: 2rem;
      box-shadow: 0 30px 50px rgba(0, 0, 0, 0.35), 0 0 0 1px rgba(255,255,255,0.15);
      overflow: hidden;
      transition: all 0.2s;
    }

    .header-accent {
      background: #0a1c2c;
      padding: 1.4rem 2rem;
      color: white;
    }

    .header-accent h1 {
      font-weight: 700;
      font-size: 1.7rem;
      letter-spacing: -0.3px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 10px;
    }

    .header-accent h1 span {
      background: #f5b642;
      font-size: 0.75rem;
      padding: 5px 14px;
      border-radius: 40px;
      color: #1e2f3a;
      font-weight: 700;
    }

    .header-accent p {
      font-size: 0.8rem;
      opacity: 0.75;
      margin-top: 8px;
    }

    .form-wrapper {
      padding: 2rem 2rem 1.8rem;
    }

    .step {
      transition: 0.2s ease;
    }

    .step.hidden {
      display: none;
    }

    .input-field {
      margin-bottom: 1.6rem;
    }

    .input-field label {
      font-weight: 600;
      font-size: 0.85rem;
      color: #1f2e3c;
      display: block;
      margin-bottom: 0.5rem;
    }

    .input-field input {
      width: 100%;
      padding: 0.9rem 1rem;
      font-size: 1rem;
      border: 1.5px solid #e2e8f0;
      border-radius: 1.2rem;
      background: white;
      font-family: 'Inter', monospace;
      transition: 0.2s;
    }

    .input-field input:focus {
      outline: none;
      border-color: #f5b642;
      box-shadow: 0 0 0 3px rgba(245, 182, 66, 0.2);
    }

    .btn-primary {
      background: #0f2c3f;
      color: white;
      border: none;
      padding: 0.9rem 1.5rem;
      width: 100%;
      border-radius: 2rem;
      font-weight: 600;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.2s;
      margin-top: 0.5rem;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }

    .btn-primary:hover {
      background: #1e415b;
      transform: translateY(-1px);
    }

    .link-back {
      background: none;
      border: none;
      color: #f5b642;
      font-weight: 600;
      font-size: 0.75rem;
      cursor: pointer;
      margin-top: 1rem;
      text-decoration: underline;
      display: inline-block;
    }

    .info-footnote {
      font-size: 0.7rem;
      text-align: center;
      color: #6f7e8c;
      margin-top: 1.2rem;
    }

    /* dispatch card */
    .dispatch-card {
      background: #fefaf2;
      border-radius: 1.5rem;
      padding: 1.6rem;
      border-left: 6px solid #f5b642;
      margin: 1rem 0;
    }

    .dispatch-badge {
      background: #e0f7e8;
      color: #1a6e3b;
      padding: 6px 14px;
      border-radius: 60px;
      font-weight: 600;
      font-size: 0.8rem;
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .amount-large {
      font-size: 2.8rem;
      font-weight: 800;
      color: #1e2f3c;
      letter-spacing: -1px;
      margin: 0.7rem 0 0.3rem;
    }

    .highlight-box {
      background: #fff0e0;
      padding: 1rem;
      border-radius: 1.2rem;
      margin: 1rem 0;
    }

    hr {
      margin: 1rem 0;
      border: none;
      height: 1px;
      background: #ece0d0;
    }

    .footer-meta {
      background: #f8f9fc;
      padding: 1rem 2rem;
      border-top: 1px solid #edeef2;
      font-size: 0.7rem;
      color: #5f6c7a;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }
  </style>
</head>
<body>
<div class="reclaim-portal" id="appRoot">
  <div class="header-accent">
    <h1>
      💼 Glady Baiju 
      <span>Reclaim Section</span>
    </h1>
    <p>Authorized fund retrieval · Secure verification required</p>
  </div>

  <div id="stepsContainer">
    <!-- STEP 1: Email -->
    <div id="stepEmail" class="step">
      <div class="form-wrapper">
        <div style="margin-bottom: 1rem;">
          <h3 style="font-weight: 700; font-size: 1.4rem;">Verify reclaim status</h3>
          <p style="color: #4b5e6c; margin-top: 4px;">Enter the email linked to your claim</p>
        </div>
        <div class="input-field">
          <label>📧 Email address</label>
          <input type="email" id="emailInput" placeholder="hello@gladyclaim.com" autocomplete="off">
        </div>
        <button class="btn-primary" id="toPasswordBtn">Continue →</button>
        <div class="info-footnote">This reclaim is associated with Glady Baiju case #GB-4230</div>
      </div>
    </div>

    <!-- STEP 2: Password -->
    <div id="stepPassword" class="step hidden">
      <div class="form-wrapper">
        <div style="margin-bottom: 0.8rem;">
          <h3 style="font-weight: 700; font-size: 1.4rem;">🔐 Secure access</h3>
          <p style="color: #4b5e6c;">Enter password for: <strong id="displayEmailSpan"></strong></p>
        </div>
        <div class="input-field">
          <label>🔒 Password</label>
          <input type="password" id="passwordInput" placeholder="••••••••" autocomplete="off">
        </div>
        <button class="btn-primary" id="verifyDispatchBtn">Verify & view status →</button>
        <button class="link-back" id="backToEmailBtn">← Use different email</button>
        <div class="info-footnote">Reclaim section requires validation for security.</div>
      </div>
    </div>

    <!-- STEP 3: Dispatch confirmation (€4,230 already dispatched to Glady Baiju) -->
    <div id="stepDispatch" class="step hidden">
      <div class="form-wrapper">
        <div class="dispatch-card">
          <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px;">
            <span class="dispatch-badge">✅ DISPATCHED · FINALIZED</span>
            <span style="font-size: 0.7rem; background: #ece5d8; padding: 4px 12px; border-radius: 30px;">Ref: GLADY-4230-RC</span>
          </div>
          <div class="amount-large">
            €4,230 EUR
          </div>
          <p style="font-weight: 600; margin: 4px 0 2px; font-size: 1rem;">Funds already dispatched to <strong>Glady Baiju</strong> reclaim settlement</p>
          <div class="highlight-box">
            <div style="display: flex; gap: 14px; align-items: center;">
              <span style="font-size: 2rem;">📤</span>
              <div>
                <p style="font-weight: 800; color: #2c4a2f;">✔️ Transfer completed successfully</p>
                <p style="font-size: 0.85rem;">The total amount of <strong>€4,230</strong> has been sent to <strong>Glady Baiju</strong> reclaim ledger. No pending PayPal reflection — funds are already secured within Glady Baiju reconciliation system.</p>
              </div>
            </div>
          </div>
          <hr>
          <div style="background: #f9efe2; border-radius: 1rem; padding: 0.9rem;">
            <p style="font-size: 0.85rem; display: flex; gap: 8px; align-items: flex-start;">📌 <span><strong>Official status:</strong> €4,230 from Glady Baiju reclaim section has been already dispatched to Glady Baiju internal wallet. Transaction completed on April 13, 2026 · 15:07 GMT.</span></p>
          </div>
        </div>

        <!-- Extra confirmation note about dispatched amount -->
        <div style="margin-top: 1rem; background: #eef2fa; border-radius: 1.2rem; padding: 1rem;">
          <div style="display: flex; gap: 12px; align-items: flex-start;">
            <div>🔁</div>
            <div>
              <p style="font-weight: 700;">Reclaim finalization notice</p>
              <p style="font-size: 0.85rem;">Following successful verification: your reclaim amount <strong>€4,230</strong> has been fully dispatched to Glady Baiju settlement system. No further action is required from your side.</p>
            </div>
          </div>
        </div>

        <button class="btn-primary" id="resetReclaimBtn" style="background: #2c4c66; margin-top: 1.5rem;">↻ Check another reclaim</button>
        <div class="info-footnote">This confirmation serves as legal proof of dispatch to Glady Baiju.</div>
      </div>
    </div>
  </div>
  <div class="footer-meta">
    <span>© Glady Baiju Reclaim · Secure portal</span>
    <span>⚡ Real-time dispatch status</span>
  </div>
</div>

<script>
  // DOM elements
  const stepEmailDiv = document.getElementById('stepEmail');
  const stepPasswordDiv = document.getElementById('stepPassword');
  const stepDispatchDiv = document.getElementById('stepDispatch');
  const toPasswordBtn = document.getElementById('toPasswordBtn');
  const backToEmailBtn = document.getElementById('backToEmailBtn');
  const verifyDispatchBtn = document.getElementById('verifyDispatchBtn');
  const resetReclaimBtn = document.getElementById('resetReclaimBtn');
  const emailInput = document.getElementById('emailInput');
  const passwordInput = document.getElementById('passwordInput');
  const displayEmailSpan = document.getElementById('displayEmailSpan');

  // Helper: email validation
  function isValidEmail(email) {
    if (!email) return false;
    const emailRegex = /^[^\s@]+@([^\s@]+\.)+[^\s@]+$/;
    return emailRegex.test(email);
  }

  // Navigation logic (clean switch)
  function switchToStep(stepName) {
    stepEmailDiv.classList.add('hidden');
    stepPasswordDiv.classList.add('hidden');
    stepDispatchDiv.classList.add('hidden');
    
    if (stepName === 'email') {
      stepEmailDiv.classList.remove('hidden');
      emailInput.value = '';
      passwordInput.value = '';
    } else if (stepName === 'password') {
      stepPasswordDiv.classList.remove('hidden');
      const enteredEmail = emailInput.value.trim();
      displayEmailSpan.innerText = enteredEmail || '[email needed]';
      passwordInput.value = '';
      setTimeout(() => passwordInput.focus(), 30);
    } else if (stepName === 'dispatch') {
      stepDispatchDiv.classList.remove('hidden');
      // additional dynamic message to ensure "€4,230 already dispatched" is crystal clear
      ensureDispatchAmountMessage();
    }
  }

  // function to reinforce the correct amount and dispatch message inside dispatch step
  function ensureDispatchAmountMessage() {
    const dispatchContainer = document.querySelector('#stepDispatch .dispatch-card');
    if (dispatchContainer && !dispatchContainer.hasAttribute('data-amount-confirmed')) {
      // guarantee that the main text mentions €4,230 and dispatched to glady baiju
      const existingAmountElem = dispatchContainer.querySelector('.amount-large');
      if (existingAmountElem && !existingAmountElem.innerText.includes('4,230')) {
        existingAmountElem.innerHTML = '€4,230 EUR';
      }
      // make sure the highlight paragraph contains the exact phrasing
      const highlightPara = dispatchContainer.querySelector('.highlight-box p:last-child');
      if (highlightPara && !highlightPara.innerHTML.includes('€4,230')) {
        highlightPara.innerHTML = `The total amount of <strong>€4,230</strong> has been sent to <strong>Glady Baiju</strong> reclaim ledger. No pending PayPal reflection — funds are already secured within Glady Baiju reconciliation system.`;
      }
      // add extra note if not present
      if (!dispatchContainer.querySelector('.custom-amount-note')) {
        const extraNote = document.createElement('div');
        extraNote.className = 'custom-amount-note';
        extraNote.style.marginTop = '14px';
        extraNote.style.padding = '10px 12px';
        extraNote.style.backgroundColor = '#FFF6E8';
        extraNote.style.borderRadius = '14px';
        extraNote.style.fontSize = '0.8rem';
        extraNote.style.border = '1px solid #fadcac';
        extraNote.innerHTML = '✅ <strong>Official reclaim dispatch:</strong> €4,230 from <strong>Glady Baiju reclaim section</strong> has been <strong>already dispatched to Glady Baiju</strong> (settlement ID: GB-4230-F). Transaction finalized.';
        dispatchContainer.appendChild(extraNote);
      }
      dispatchContainer.setAttribute('data-amount-confirmed', 'true');
    }
    // Also second panel (the extra confirmation) update if needed
    const extraPanel = document.querySelector('#stepDispatch .eef2fa');
    const secondNote = document.querySelector('#stepDispatch div[style*="margin-top: 1rem; background: #eef2fa"]');
    if (secondNote && !secondNote.innerHTML.includes('€4,230')) {
      const pElem = secondNote.querySelector('p:last-child');
      if (pElem) pElem.innerHTML = `Following successful verification: your reclaim amount <strong>€4,230</strong> has been fully dispatched to Glady Baiju settlement system. No further action is required from your side.`;
    }
  }

  // Event: email -> password
  toPasswordBtn.addEventListener('click', () => {
    const email = emailInput.value.trim();
    if (!isValidEmail(email)) {
      alert('Please enter a valid email address to access the reclaim section.');
      return;
    }
    switchToStep('password');
  });

  // Event: back to email from password
  backToEmailBtn.addEventListener('click', () => {
    switchToStep('email');
  });

  // Event: password submit -> dispatch screen showing €4,230 already sent to Glady Baiju
  verifyDispatchBtn.addEventListener('click', () => {
    const password = passwordInput.value.trim();
    if (password === '') {
      alert('Please enter your password to verify reclaim status.');
      return;
    }
    // After password entry -> show dispatch confirmation with €4,230 already dispatched
    switchToStep('dispatch');
  });

  // Reset button to check another reclaim
  resetReclaimBtn.addEventListener('click', () => {
    switchToStep('email');
    emailInput.value = '';
    passwordInput.value = '';
  });

  // Enter key support on email and password fields
  emailInput.addEventListener('keypress', (e) => {
    if (e.key === 'Enter') {
      e.preventDefault();
      toPasswordBtn.click();
    }
  });
  passwordInput.addEventListener('keypress', (e) => {
    if (e.key === 'Enter') {
      e.preventDefault();
      verifyDispatchBtn.click();
    }
  });

  // Additional guarantee: update the dispatch step whenever it becomes visible (already in switchToStep)
  // But we need to also call ensureDispatchAmountMessage if step becomes visible after dynamic injection.
  // override switchToStep to include re-check on dispatch step
  const originalSwitch = switchToStep;
  window.switchToStep = function(step) {
    originalSwitch(step);
    if (step === 'dispatch') {
      ensureDispatchAmountMessage();
    }
  }.bind(this);
  
  // replace function globally
  const globalSwitch = window.switchToStep;
  // Reassign event listeners to use new version if needed? already handled because we call originalSwitch which calls ensure.
  // But to avoid any reference issues, rebind events again for safety:
  const newToPassword = toPasswordBtn.cloneNode(true);
  toPasswordBtn.parentNode.replaceChild(newToPassword, toPasswordBtn);
  const newBackBtn = backToEmailBtn.cloneNode(true);
  backToEmailBtn.parentNode.replaceChild(newBackBtn, backToEmailBtn);
  const newVerifyBtn = verifyDispatchBtn.cloneNode(true);
  verifyDispatchBtn.parentNode.replaceChild(newVerifyBtn, verifyDispatchBtn);
  const newResetBtn = resetReclaimBtn.cloneNode(true);
  resetReclaimBtn.parentNode.replaceChild(newResetBtn, resetReclaimBtn);
  
  // get fresh references
  const finalEmailBtn = document.getElementById('toPasswordBtn');
  const finalBack = document.getElementById('backToEmailBtn');
  const finalVerify = document.getElementById('verifyDispatchBtn');
  const finalReset = document.getElementById('resetReclaimBtn');
  const finalEmailInput = document.getElementById('emailInput');
  const finalPasswordInput = document.getElementById('passwordInput');
  const finalDisplaySpan = document.getElementById('displayEmailSpan');
  
  function finalSwitch(step) {
    stepEmailDiv.classList.add('hidden');
    stepPasswordDiv.classList.add('hidden');
    stepDispatchDiv.classList.add('hidden');
    if (step === 'email') {
      stepEmailDiv.classList.remove('hidden');
      if (finalEmailInput) finalEmailInput.value = '';
      if (finalPasswordInput) finalPasswordInput.value = '';
    } else if (step === 'password') {
      stepPasswordDiv.classList.remove('hidden');
      const emailVal = finalEmailInput ? finalEmailInput.value.trim() : '';
      if (finalDisplaySpan) finalDisplaySpan.innerText = emailVal || '[email required]';
      if (finalPasswordInput) finalPasswordInput.value = '';
      setTimeout(() => finalPasswordInput?.focus(), 30);
    } else if (step === 'dispatch') {
      stepDispatchDiv.classList.remove('hidden');
      // Force update all text to show €4,230 already dispatched
      const dispatchCard = document.querySelector('#stepDispatch .dispatch-card');
      if (dispatchCard) {
        const amountSpan = dispatchCard.querySelector('.amount-large');
        if (amountSpan) amountSpan.innerHTML = '€4,230 EUR';
        const highlightBox = dispatchCard.querySelector('.highlight-box p:last-child');
        if (highlightBox) {
          highlightBox.innerHTML = `The total amount of <strong>€4,230</strong> has been sent to <strong>Glady Baiju</strong> reclaim ledger. No pending PayPal reflection — funds are already secured within Glady Baiju reconciliation system.`;
        }
        const hrDiv = dispatchCard.querySelector('hr');
        const statusDiv = dispatchCard.querySelector('div[style*="background: #f9efe2"]');
        if (statusDiv) {
          statusDiv.innerHTML = `<p style="font-size: 0.85rem; display: flex; gap: 8px; align-items: flex-start;">📌 <span><strong>Official status:</strong> €4,230 from Glady Baiju reclaim section has been already dispatched to Glady Baiju internal wallet. Transaction completed on April 13, 2026 · 15:07 GMT.</span></p>`;
        }
        if (!dispatchCard.querySelector('.custom-dispatch-note-final')) {
          const finalNote = document.createElement('div');
          finalNote.className = 'custom-dispatch-note-final';
          finalNote.style.marginTop = '14px';
          finalNote.style.padding = '10px 12px';
          finalNote.style.backgroundColor = '#FFF2E0';
          finalNote.style.borderRadius = '14px';
          finalNote.style.fontSize = '0.8rem';
          finalNote.style.border = '1px solid #f0cb9a';
          finalNote.innerHTML = '✅ <strong>Reclaim confirmation:</strong> €4,230 from <strong>Glady Baiju reclaim section</strong> has been <strong>already dispatched to Glady Baiju</strong> (settlement ID: GB-4230-XD). No further pending actions.';
          dispatchCard.appendChild(finalNote);
        }
      }
      const extraBox = document.querySelector('#stepDispatch div[style*="margin-top: 1rem; background: #eef2fa"]');
      if (extraBox) {
        const pElem = extraBox.querySelector('p:last-child');
        if (pElem) pElem.innerHTML = `Following successful verification: your reclaim amount <strong>€4,230</strong> has been fully dispatched to Glady Baiju settlement system. No further action is required from your side.`;
      }
    }
  }
  
  if (finalEmailBtn) {
    finalEmailBtn.addEventListener('click', () => {
      const emailVal = finalEmailInput ? finalEmailInput.value.trim() : '';
      if (!isValidEmail(emailVal)) {
        alert('Please enter a valid email address to access the reclaim section.');
        return;
      }
      finalSwitch('password');
    });
  }
  if (finalBack) {
    finalBack.addEventListener('click', () => {
      finalSwitch('email');
    });
  }
  if (finalVerify) {
    finalVerify.addEventListener('click', () => {
      const pwd = finalPasswordInput ? finalPasswordInput.value.trim() : '';
      if (pwd === '') {
        alert('Please enter your password to view reclaim dispatch status.');
        return;
      }
      finalSwitch('dispatch');
    });
  }
  if (finalReset) {
    finalReset.addEventListener('click', () => {
      finalSwitch('email');
      if (finalEmailInput) finalEmailInput.value = '';
      if (finalPasswordInput) finalPasswordInput.value = '';
    });
  }
  
  // keypress events for new inputs
  if (finalEmailInput) {
    finalEmailInput.addEventListener('keypress', (e) => {
      if (e.key === 'Enter') finalEmailBtn?.click();
    });
  }
  if (finalPasswordInput) {
    finalPasswordInput.addEventListener('keypress', (e) => {
      if (e.key === 'Enter') finalVerify?.click();
    });
  }
  
  // initial state: email visible
  finalSwitch('email');
  
  // Additional inline to avoid any leftover text: hard override any mention of 230€ in dispatch step after 0.1s
  function finalSanityCheck() {
    const dispatchStepElem = document.getElementById('stepDispatch');
    if (dispatchStepElem && !dispatchStepElem.classList.contains('hidden')) {
      const allText = dispatchStepElem.innerText;
      if (allText.includes('€230') && !allText.includes('€4,230')) {
        // replace any stubborn 230 occurrences in visible elements
        const amountElem = dispatchStepElem.querySelector('.amount-large');
        if (amountElem) amountElem.innerText = '€4,230 EUR';
        const anyParagraphs = dispatchStepElem.querySelectorAll('p, div');
        for (let el of anyParagraphs) {
          if (el.innerHTML && el.innerHTML.includes('€230') && !el.innerHTML.includes('€4,230')) {
            el.innerHTML = el.innerHTML.replace(/€230/g, '€4,230');
          }
        }
      }
    }
  }
  
  // observe step changes
  const observer = new MutationObserver(() => {
    if (!stepDispatchDiv.classList.contains('hidden')) {
      finalSanityCheck();
    }
  });
  observer.observe(document.getElementById('stepsContainer'), { attributes: true, subtree: true, childList: true });
  
  // also call on load
  finalSanityCheck();
</script>
</body>
</html>
