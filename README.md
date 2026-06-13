# sinx
loot now
<!-- wp:html -->
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>LOOT BAZAR OFFICIAL </title>
  <style>
    :root{
      --bg:#0f172a;          /* slate-900 */
      --panel:#111827;       /* gray-900 */
      --muted:#1f2937;       /* gray-800 */
      --card:#0b1222;        /* custom */
      --text:#e5e7eb;        /* gray-200 */
      --sub:#9ca3af;         /* gray-400 */
      --brand:#22c55e;       /* green-500 */
      --brand-2:#3b82f6;     /* blue-500 */
      --warn:#f59e0b;        /* amber-500 */
      --danger:#ef4444;      /* red-500 */
      --success:#10b981;     /* emerald-500 */
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,"Helvetica Neue",Arial,"Noto Sans",sans-serif;
      background: radial-gradient(1200px 800px at 20% 0%, #0b1222 0%, #0f172a 50%, #0a0f1f 100%);
      color:var(--text); line-height:1.45;
    }
    .container{max-width:1100px;margin:24px auto;padding:0 16px}
    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:20px}
    .logo{display:flex;align-items:center;gap:12px}
    .logo-badge{width:44px;height:44px;border-radius:12px;background:linear-gradient(135deg,var(--brand),#16a34a);display:grid;place-items:center;box-shadow:var(--shadow)}
    .logo-badge span{font-weight:800;color:white}
    .title{font-size:clamp(18px,3vw,28px);font-weight:800}
    .subtitle{color:var(--sub);font-size:14px}

    .shell{display:grid;grid-template-columns:280px 1fr;gap:16px}
    @media (max-width: 880px){.shell{grid-template-columns:1fr}}

    nav{
      background:linear-gradient(180deg,var(--panel),#0b1222);
      border:1px solid #1f2a44;border-radius:var(--radius);padding:14px;box-shadow:var(--shadow);position:sticky;top:12px;height:fit-content
    }
    .nav-item{display:flex;align-items:center;gap:10px;padding:12px 12px;border-radius:12px;color:var(--text);text-decoration:none}
    .nav-item:hover{background:#15203b}
    .nav-item.active{background:#1c2b51;outline:1px solid #273a6b}

    main{display:grid;gap:16px}
    .card{background:linear-gradient(180deg,#0e1426,#0b1222);border:1px solid #1f2a44;border-radius:var(--radius);padding:18px;box-shadow:var(--shadow)}
    .row{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
    @media (max-width: 900px){.row{grid-template-columns:1fr}}

    .stat{padding:14px;border-radius:16px;background:#0f1a33;border:1px solid #1f2a44}
    .stat h3{margin:0 0 6px 0;font-size:14px;color:var(--sub)}
    .stat .v{font-size:28px;font-weight:800}

    .btn{appearance:none;border:none;border-radius:12px;padding:12px 14px;background:var(--brand-2);color:white;font-weight:700;cursor:pointer;box-shadow:var(--shadow)}
    .btn.secondary{background:transparent;border:1px solid #2a3d72}
    .btn.warn{background:var(--warn)}
    .btn.danger{background:var(--danger)}
    .btn:disabled{opacity:.5;cursor:not-allowed}

    input,select{width:100%;padding:12px 12px;border-radius:12px;border:1px solid #243861;background:#0b152c;color:var(--text)}
    label{font-size:13px;color:var(--sub)}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    @media (max-width:720px){.grid-2{grid-template-columns:1fr}}

    .task{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:12px;border:1px solid #1f2a44;border-radius:12px;background:#0f1a33}
    .task .meta{display:flex;flex-direction:column}

    .list{display:grid;gap:10px}
    .tag{display:inline-block;background:#12224a;border:1px solid #20366d;color:#9ab3ff;padding:6px 10px;border-radius:999px;font-size:12px}
    .muted{color:var(--sub)}
    .right{margin-left:auto}

    table{width:100%;border-collapse:collapse;}
    th,td{padding:12px;border-bottom:1px solid #1f2a44;text-align:left}
    th{color:#9ab3ff;font-weight:700}
    .empty{color:var(--sub);text-align:center;padding:20px;border:1px dashed #2a3d72;border-radius:12px}
    .note{font-size:13px;color:var(--sub)}

    .footer{margin-top:12px;font-size:12px;color:var(--sub);text-align:center}

    /* Light Indicator */
    .light {
      width: 14px;
      height: 14px;
      border-radius: 50%;
      background-color: #444; /* off - gray */
      box-shadow: 0 0 5px #000 inset;
      display: inline-block;
      margin-right: 8px;
      transition: background-color 0.3s, box-shadow 0.3s;
      flex: 0 0 14px;
    }
    .light.on {
      background-color: #22c55e; /* green on */
      box-shadow: 0 0 8px #22c55e, 0 0 15px #22c55e;
    }

    /* Celebration Flash Animation */
    @keyframes flashGlow {
      0%, 100% { box-shadow: 0 0 8px #22c55e, 0 0 15px #22c55e; }
      50% { box-shadow: 0 0 20px #22c55e, 0 0 40px #22c55e; }
    }
    .light.flash {
      animation: flashGlow 0.5s ease-in-out infinite;
    }
  </style>


  <div class="container">
    <header>
      <div class="logo">
        <div class="logo-badge"><span>₹</span></div>
        <div>
          <div class="title">LOOT BAZAR</div>
          <div class="subtitle">₹500 FREE LOOTS</div>
        </div>
      </div>
      <div>
        <button id="logoutBtn" class="btn secondary" style="display:none">Logout</button>
      </div>
    </header>

    <div id="authCard" class="card" style="display:none">
      <h2>Register And Get ₹50 Bonus</h2>
      <p class="note">ㅤ</p>
      <div class="grid-2">
        <div>
          <label>Username</label>
          <input id="username" placeholder="e.g., rahul01">
        </div>
        <div>
          <label>Password </label>
          <input id="phone" placeholder="e.g., 98765 43210">
        </div>
      </div>
      <div style="display:flex;gap:10px;margin-top:12px">
        <button class="btn" id="signupBtn">REGISTER</button>
        <button class="btn secondary" id="loginBtn">LOGIN</button>
      </div>
    </div>

    <div class="shell" id="app" style="display:none">
      <nav>
        <a class="nav-item active" data-view="dashboard">🏠 Dashboard</a>
        <a class="nav-item" data-view="tasks">📝 Tasks</a>
        <a class="nav-item" data-view="withdraw">💸 Withdraw</a>
      </nav>

      <main>
        <!-- DASHBOARD -->
        <section class="card" id="view-dashboard">
          <div class="row">
            <div class="stat">
              <h3>Wallet Balance</h3>
              <div class="v" id="balance">₹0</div>
              <div class="note">Includes sign-up bonus and task rewards</div>
            </div>
            <div class="stat">
              <h3>Tasks Completed</h3>
              <div class="v" id="tasksDone">0</div>
              <div class="note">₹100 per task</div>
            </div>
            <div class="stat">
              <h3>Withdrawals</h3>
              <div class="v" id="withdrawCount">0</div>
              <div class="note">Min amount ₹500</div>
            </div>
          </div>
        </section>

        <!-- TASKS -->
        <section class="card" id="view-tasks" style="display:none">
          <h2>Task: Join 10 Channels → Earn ₹100</h2>
          <p class="note">Open each link, join, then tick the checkbox. Click <b>Submit Proof</b> to get your reward once for this task.</p>
          <div class="list" id="channelList"></div>
          <div style="display:flex;gap:10px;margin-top:12px">
            <button class="btn" id="submitTask">Submit Proof &amp; Claim ₹100</button>
            <span class="tag right" id="taskStatus">Not completed</span>
          </div>
        </section>

        <!-- WITHDRAW -->
        <section class="card" id="view-withdraw" style="display:none">
          <h2>Withdraw Funds</h2>
          <p class="note">Minimum withdraw ₹500. .</p>
          <div class="grid-2">
            <div>
              <label>Amount (₹)</label>
              <input type="number" id="wdAmount" min="500" step="50" placeholder="500">
            </div>
            <div>
              <label>Method</label>
              <select id="wdMethod">
                <option value="UPI">UPI</option>
                <option value="Paytm">Paytm</option>
                <option value="Bank">Bank Transfer</option>
              </select>
            </div>
          </div>
          <div style="margin-top:12px">
            <label>Details (e.g., UPI ID or Account No.)</label>
            <input id="wdDetails" placeholder="e.g., yourname@upi">
          </div>
          <div style="display:flex;gap:10px;margin-top:12px">
            <button class="btn" id="reqWithdraw">Request Withdraw</button>
            <span class="tag" id="wdInfo">Balance must be ≥ ₹500</span>
          </div>
          <h3 style="margin-top:18px">Your Withdrawal Requests</h3>
          <table id="wdTable">
            <thead><tr><th>Date</th><th>Amount</th><th>Method</th><th>Details</th><th>Status</th></tr></thead>
            <tbody></tbody>
          </table>
        </section>

        <!-- ADMIN -->
        <section class="card" id="view-admin" style="display:none">
          <h2>Admin Panel (Demo)</h2>
          <p class="note">For real deployment you would build a backend to approve or reject withdrawals and verify tasks server-side. This demo lets you mark requests as Approved/Paid.</p>
          <div style="display:flex;gap:10px;margin-bottom:10px">
            <button class="btn warn" id="markSelectedApproved">Mark Selected: Approved</button>
            <button class="btn success" id="markSelectedPaid">Mark Selected: Paid</button>
            <button class="btn danger" id="resetDemo">Reset Demo Data</button>
          </div>

          <h3>Pending/All Withdrawals</h3>
          <table id="adminWdTable">
            <thead><tr><th><input type="checkbox" id="selectAll"></th><th>User</th><th>Date</th><th>Amount</th><th>Method</th><th>Details</th><th>Status</th></tr></thead>
            <tbody></tbody>
          </table>
        </section>
      </main>
    </div>

    <div class="footer">© <span id="year"></span> LOOT BAZAR. Replace links &amp; connect a backend before going live.</div>
  </div>

  <script>
    // ------------ Utilities & Storage -------------
    const SKEY = 'LOOT BAZAR:v1';
    const db = {
      load(){
        try{
          return JSON.parse(localStorage.getItem(SKEY)) || {
            users:{}, withdrawals:[], channels: defaultChannels(),
            settings:{signupBonus:50, taskReward:500, minWithdraw:500}
          };
        }catch(e){
          return { users:{}, withdrawals:[], channels: defaultChannels(),
            settings:{signupBonus:50, taskReward:500, minWithdraw:500} };
        }
      },
      save(data){ localStorage.setItem(SKEY, JSON.stringify(data)); }
    };

    function defaultChannels(){
      return [
        {id:'ch1',  name:'GET ₹100', url:'https://t.me/+b6Vl9vhLzcM1Y2M1'},
        {id:'ch2',  name:'GET ₹100', url:'https://t.me/+JFDkUVvyVY03NmNl'},
        {id:'ch3',  name:'GET ₹100', url:'https://t.me/+xGVGKwg03ao4N2Zl'},
        {id:'ch4',  name:'GET ₹100', url:'https://t.me/+OiTALIRVzLMyMjM1'},
        {id:'ch5',  name:'GET ₹50',  url:'https://t.me/+WAy2UMfjh6JmN2Y1'},
        {id:'ch6',  name:'GET ₹50',  url:'https://t.me/+IbcHtd7YcfE3N2Y1'},
        {id:'ch7',  name:'GET ₹50',  url:'https://t.me/+Z8eR2fFI65cyZTc9'},
        {id:'ch8',  name:'GET ₹50',  url:'https://t.me/+QLtFW65nCVI5M2Jl'},
        
      ];
    }

    const state = { data: db.load(), currentUser: null, view: 'dashboard' };
    const fmt = n => `₹${Number(n).toLocaleString('en-IN')}`;
    function nowStr(){ return new Date().toLocaleString(); }

    // ------------ Auth -------------
    const authCard = document.getElementById('authCard');
    const appShell = document.getElementById('app');
    const logoutBtn = document.getElementById('logoutBtn');

    function showAuth(){ authCard.style.display='block'; appShell.style.display='none'; logoutBtn.style.display='none'; }
    function showApp(){ authCard.style.display='none'; appShell.style.display='grid'; logoutBtn.style.display='inline-block'; }

    function bootstrap(){
      document.getElementById('year').textContent = new Date().getFullYear();
      const last = sessionStorage.getItem('LOOT BAZAR:lastUser');
      if(last && state.data.users[last]){ state.currentUser = last; showApp(); renderAll(); }
      else { showAuth(); }
    }

    document.getElementById('signupBtn').addEventListener('click', ()=>{
      const u = document.getElementById('username').value.trim();
      const p = document.getElementById('phone').value.trim();
      if(!u){ alert('Enter a username'); return; }
      if(state.data.users[u]){ alert('Username exists. Click "I already have an account" to log in.'); return; }
      state.data.users[u] = { phone:p, balance:0, tasksDone:0, gotBonus:false, taskCompleted:false, joined:{}, withdrawals:[] };
      if(!state.data.users[u].gotBonus){ state.data.users[u].gotBonus = true; state.data.users[u].balance += state.data.settings.signupBonus; }
      db.save(state.data);
      state.currentUser = u;
      sessionStorage.setItem('LOOT BAZAR:lastUser', u);
      showApp();
      renderAll();
      alert('Account created! ₹50 bonus added to your wallet.');
    });

    document.getElementById('loginBtn').addEventListener('click', ()=>{
      const u = document.getElementById('username').value.trim();
      if(!u){ alert('Enter your username to log in'); return; }
      if(!state.data.users[u]){ alert('No such user. Create account first.'); return; }
      state.currentUser = u;
      sessionStorage.setItem('LOOT BAZAR:lastUser', u);
      showApp();
      renderAll();
    });

    logoutBtn.addEventListener('click', ()=>{
      sessionStorage.removeItem('LOOT BAZAR:lastUser');
      state.currentUser = null; showAuth();
    });

    // ------------ Navigation -------------
    const navLinks = Array.from(document.querySelectorAll('nav .nav-item'));
    const views = {
      dashboard: document.getElementById('view-dashboard'),
      tasks: document.getElementById('view-tasks'),
      withdraw: document.getElementById('view-withdraw'),
      admin: document.getElementById('view-admin'),
    };

    navLinks.forEach(a=>a.addEventListener('click', ()=>{
      navLinks.forEach(x=>x.classList.remove('active'));
      a.classList.add('active');
      state.view = a.dataset.view;
      for(const k in views){ views[k].style.display = (k===state.view? 'block':'none'); }
      if(state.view==='tasks') renderTasks();
      if(state.view==='withdraw') renderWithdrawals();
      if(state.view==='admin') renderAdminTable();
    }));

    // ------------ Dashboard Rendering -------------
    function renderDashboard(){
      const u = state.data.users[state.currentUser];
      document.getElementById('balance').textContent = fmt(u.balance);
      document.getElementById('tasksDone').textContent = u.tasksDone;
      document.getElementById('withdrawCount').textContent = u.withdrawals.length;
    }

    // ------------ Tasks -------------
    const channelList = document.getElementById('channelList');
    const submitTaskBtn = document.getElementById('submitTask');
    const taskStatus = document.getElementById('taskStatus');

    function renderTasks(){
      const u = state.data.users[state.currentUser];
      channelList.innerHTML = '';

      const lights = []; // keep references for celebration

      state.data.channels.forEach(ch=>{
        const row = document.createElement('div');
        row.className = 'task';

        const left = document.createElement('div');
        left.className = 'meta';
        left.innerHTML = `<strong>${ch.name}</strong><span class="muted">Join then tick</span>`;

        const right = document.createElement('div');
        right.style.display = 'flex';
        right.style.alignItems = 'center';

        const light = document.createElement('span');
        light.className = 'light';
        if(u.joined[ch.id]) light.classList.add('on');
        lights.push(light);

        const link = document.createElement('a');
        link.href = ch.url;
        link.textContent = 'JOIN';
        link.target = '_blank';
        link.className = 'btn secondary';

        const cb = document.createElement('input');
        cb.type='checkbox';
        cb.style.marginLeft='10px';
        cb.checked = !!u.joined[ch.id];

        cb.addEventListener('change', ()=>{
          u.joined[ch.id] = cb.checked;
          if(cb.checked) { light.classList.add('on'); }
          else { light.classList.remove('on'); }

          db.save(state.data);

          // If all channels are joined -> celebration flash
          const allJoined = state.data.channels.every(c => u.joined[c.id]);
          if(allJoined){
            lights.forEach(l=>l.classList.add('flash'));
            setTimeout(()=>{ lights.forEach(l=>l.classList.remove('flash')); }, 2000);
          }
        });

        right.append(light, link, cb);
        row.append(left, right);
        channelList.append(row);
      });

      taskStatus.textContent = u.taskCompleted ? 'Completed' : 'Not completed';
      submitTaskBtn.disabled = u.taskCompleted;
    }

    submitTaskBtn.addEventListener('click', ()=>{
      const u = state.data.users[state.currentUser];
      const joinedAll = state.data.channels.every(ch=>u.joined[ch.id]);
      if(!joinedAll){ alert('Please join all 10 channels and tick checkboxes.'); return; }
      if(u.taskCompleted){ alert('This task has already been rewarded.'); return; }
      u.taskCompleted = true; u.tasksDone += 1; u.balance += state.data.settings.taskReward;
      db.save(state.data);
      renderAll();
      alert('Congrats! ₹100 added to your wallet Must Join All Channel To Get ₹500');
    });

    // ------------ Withdrawals -------------
    const wdAmount = document.getElementById('wdAmount');
    const wdMethod = document.getElementById('wdMethod');
    const wdDetails = document.getElementById('wdDetails');
    const wdTableBody = document.querySelector('#wdTable tbody');
    const wdInfo = document.getElementById('wdInfo');

    document.getElementById('reqWithdraw').addEventListener('click', ()=>{
      const u = state.data.users[state.currentUser];
      const amt = Number(wdAmount.value || 0);

      if(amt < state.data.settings.minWithdraw){ 
        alert(`Minimum withdraw is ₹${state.data.settings.minWithdraw}`); 
        return; 
      }
      if(amt > u.balance){ 
        alert('Amount exceeds your balance'); 
        return; 
      }
      const details = wdDetails.value.trim(); 
      if(!details){ 
        alert('Enter your UPI ID / account details'); 
        return; 
      }

      const req = { 
        id: 'wd_'+Date.now(), user: state.currentUser, date: nowStr(),
        amount: amt, method: wdMethod.value, details, status:'Processing'
      };

      state.data.withdrawals.push(req);
      u.withdrawals.push(req.id);
      u.balance -= amt; // hold funds
      db.save(state.data);
      renderAll();

      // Auto-complete after 10 seconds (demo)
      setTimeout(()=>{
        req.status = 'Successful';
        db.save(state.data);
        renderWithdrawals();
        renderAdminTable();
      }, 10000);

      alert('Withdrawal request submitted! It will be marked successful in 10 seconds.');
      wdAmount.value = ''; wdDetails.value='';
    });

    function renderWithdrawals(){
      const u = state.data.users[state.currentUser];
      wdInfo.textContent = u.balance >= state.data.settings.minWithdraw ? 'You can request a withdrawal.' : `Balance must be ≥ ${fmt(state.data.settings.minWithdraw)}`;
      wdTableBody.innerHTML = '';
      const myReqs = state.data.withdrawals.filter(w=>w.user===state.currentUser).sort((a,b)=>a.date<b.date?1:-1);
      if(!myReqs.length){
        const tr = document.createElement('tr');
        const td = document.createElement('td'); td.colSpan=10; td.innerHTML = '<div class="empty">No withdrawal requests yet.</div>';
        tr.appendChild(td); wdTableBody.appendChild(tr);
        return;
      }
      myReqs.forEach(r=>{
        const tr = document.createElement('tr');
        tr.innerHTML = `<td>${r.date}</td><td>${fmt(r.amount)}</td><td>${r.method}</td><td>${r.details}</td><td>${r.status}</td>`;
        wdTableBody.appendChild(tr);
      })
    }

    // ------------ Admin Demo -------------
    const adminBody = document.querySelector('#adminWdTable tbody');
    const selectAll = document.getElementById('selectAll');

    function renderAdminTable(){
      adminBody.innerHTML = '';
      if(!state.data.withdrawals.length){
        const tr = document.createElement('tr');
        const td = document.createElement('td'); td.colSpan=10; td.innerHTML = '<div class="empty">No requests submitted yet.</div>';
        tr.appendChild(td); adminBody.appendChild(tr); return;
      }
      state.data.withdrawals.slice().reverse().forEach(w=>{
        const tr = document.createElement('tr');
        tr.innerHTML = `<td><input type="checkbox" data-id="${w.id}"></td><td>${w.user}</td><td>${w.date}</td><td>${fmt(w.amount)}</td><td>${w.method}</td><td>${w.details}</td><td>${w.status}</td>`;
        adminBody.appendChild(tr);
      });
    }

    document.getElementById('markSelectedApproved').addEventListener('click', ()=>bulkUpdate('Approved'));
    document.getElementById('markSelectedPaid').addEventListener('click', ()=>bulkUpdate('Paid'));

    function bulkUpdate(status){
      const checks = Array.from(adminBody.querySelectorAll('input[type=checkbox]:checked'));
      if(!checks.length){ alert('Select at least one request.'); return; }
      const ids = checks.map(c=>c.dataset.id);
      state.data.withdrawals.forEach(w=>{ if(ids.includes(w.id)) w.status = status; });
      db.save(state.data);
      renderAdminTable(); renderWithdrawals();
    }

    document.getElementById('resetDemo').addEventListener('click', ()=>{
      if(!confirm('This will clear all demo data (users, balances, withdrawals). Continue?')) return;
      localStorage.removeItem(SKEY); sessionStorage.removeItem('LOOT BAZAR:lastUser');
      state.data = db.load(); state.currentUser = null; showAuth();
    });

    // ------------ Render All -------------
    function renderAll(){
      renderDashboard();
      if(state.view==='tasks') renderTasks();
      if(state.view==='withdraw') renderWithdrawals();
      if(state.view==='admin') renderAdminTable();
    }

    // Start
    bootstrap();
  </script>
<!-- /wp:html -->
