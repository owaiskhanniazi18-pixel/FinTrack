<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FinTrack — Smart Money Planner</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #0d1117;
      --surface: #161b22;
      --surface2: #1c2330;
      --border: #30363d;
      --green: #3fb950;
      --green-dim: #1a3826;
      --red: #f85149;
      --red-dim: #3d1a1a;
      --amber: #d29922;
      --amber-dim: #3d2e00;
      --blue: #58a6ff;
      --text: #e6edf3;
      --muted: #8b949e;
      --accent: #3fb950;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      line-height: 1.6;
    }

    /* ── NAV ── */
    nav {
      position: sticky; top: 0; z-index: 100;
      background: rgba(13,17,23,0.85);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--border);
      padding: 0 32px;
      display: flex; align-items: center; justify-content: space-between;
      height: 60px;
    }
    .nav-brand {
      font-family: 'DM Serif Display', serif;
      font-size: 1.35rem;
      color: var(--green);
      letter-spacing: -0.5px;
    }
    .nav-brand span { color: var(--text); }
    .nav-links { display: flex; gap: 28px; list-style: none; }
    .nav-links a { color: var(--muted); text-decoration: none; font-size: .88rem; font-weight: 500; transition: color .2s; }
    .nav-links a:hover { color: var(--text); }

    /* ── HERO ── */
    .hero {
      text-align: center;
      padding: 80px 20px 56px;
      position: relative;
      overflow: hidden;
    }
    .hero::before {
      content: '';
      position: absolute; inset: 0;
      background: radial-gradient(ellipse 60% 50% at 50% 0%, rgba(63,185,80,.12) 0%, transparent 70%);
      pointer-events: none;
    }
    .hero-badge {
      display: inline-flex; align-items: center; gap: 6px;
      background: var(--green-dim); color: var(--green);
      border: 1px solid rgba(63,185,80,.3);
      border-radius: 20px; padding: 4px 14px;
      font-size: .78rem; font-weight: 600; letter-spacing: .5px;
      margin-bottom: 20px;
    }
    .hero h1 {
      font-family: 'DM Serif Display', serif;
      font-size: clamp(2.2rem, 5vw, 3.6rem);
      line-height: 1.15;
      letter-spacing: -1px;
      margin-bottom: 16px;
    }
    .hero h1 em { color: var(--green); font-style: normal; }
    .hero p {
      color: var(--muted); font-size: 1.05rem; max-width: 480px;
      margin: 0 auto 36px;
    }
    .hero-stats {
      display: flex; gap: 48px; justify-content: center;
      flex-wrap: wrap; margin-bottom: 16px;
    }
    .hero-stat { text-align: center; }
    .hero-stat strong { display: block; font-size: 1.7rem; font-weight: 600; color: var(--green); }
    .hero-stat span { font-size: .8rem; color: var(--muted); text-transform: uppercase; letter-spacing: .5px; }

    /* ── LAYOUT ── */
    .main { max-width: 1100px; margin: 0 auto; padding: 0 20px 80px; }

    /* ── SECTION LABELS ── */
    .section-label {
      font-size: .72rem; font-weight: 600;
      letter-spacing: 1.5px; text-transform: uppercase;
      color: var(--muted); margin-bottom: 12px;
    }
    .section-title {
      font-family: 'DM Serif Display', serif;
      font-size: 1.5rem; margin-bottom: 24px;
      letter-spacing: -.3px;
    }

    /* ── CARDS ── */
    .card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 24px;
      transition: border-color .2s;
    }
    .card:hover { border-color: rgba(63,185,80,.3); }
    .card h2 {
      font-family: 'DM Serif Display', serif;
      font-size: 1.15rem; margin-bottom: 16px;
      display: flex; align-items: center; gap: 8px;
    }
    .card h2 .icon {
      width: 32px; height: 32px; border-radius: 8px;
      display: flex; align-items: center; justify-content: center;
      font-size: 1rem;
    }

    /* ── GRID LAYOUTS ── */
    .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 20px; }
    .grid-3 { display: grid; grid-template-columns: repeat(3,1fr); gap: 16px; margin-bottom: 20px; }
    .span-2 { grid-column: span 2; }
    @media(max-width:700px) {
      .grid-2, .grid-3 { grid-template-columns: 1fr; }
      .span-2 { grid-column: span 1; }
    }

    /* ── INPUTS ── */
    .field { margin-bottom: 12px; }
    .field label { display: block; font-size: .8rem; font-weight: 500; color: var(--muted); margin-bottom: 6px; }
    .field input, .field select {
      width: 100%;
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: 8px;
      color: var(--text);
      padding: 10px 14px;
      font-family: inherit; font-size: .93rem;
      outline: none; transition: border-color .2s;
    }
    .field input:focus, .field select:focus { border-color: var(--green); }
    .field select option { background: var(--surface); }

    /* ── BUTTONS ── */
    .btn {
      display: inline-flex; align-items: center; justify-content: center; gap: 6px;
      padding: 10px 20px; border: none; border-radius: 8px;
      font-family: inherit; font-size: .9rem; font-weight: 600;
      cursor: pointer; transition: all .2s; width: 100%;
    }
    .btn-green { background: var(--green); color: #000; }
    .btn-green:hover { background: #4dd664; transform: translateY(-1px); box-shadow: 0 4px 16px rgba(63,185,80,.35); }
    .btn-red { background: var(--red); color: #fff; }
    .btn-red:hover { background: #ff6059; transform: translateY(-1px); }
    .btn-ghost { background: var(--surface2); color: var(--text); border: 1px solid var(--border); }
    .btn-ghost:hover { background: var(--surface); }

    /* ── SUMMARY METRICS ── */
    .metric {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 20px;
      position: relative; overflow: hidden;
    }
    .metric::after {
      content: attr(data-icon);
      position: absolute; right: 16px; top: 50%;
      transform: translateY(-50%);
      font-size: 2rem; opacity: .12;
    }
    .metric .label { font-size: .78rem; color: var(--muted); text-transform: uppercase; letter-spacing: .5px; margin-bottom: 6px; }
    .metric .value { font-size: 1.7rem; font-weight: 600; }
    .metric .sub { font-size: .78rem; color: var(--muted); margin-top: 4px; }
    .metric.green-glow { border-color: rgba(63,185,80,.3); }
    .metric.red-glow { border-color: rgba(248,81,73,.3); }
    .metric.blue-glow { border-color: rgba(88,166,255,.3); }

    /* ── PROGRESS BAR ── */
    .progress-wrap { margin: 16px 0 8px; }
    .progress-label { display: flex; justify-content: space-between; font-size: .8rem; color: var(--muted); margin-bottom: 6px; }
    .progress-track { background: var(--bg); border-radius: 99px; height: 8px; overflow: hidden; }
    .progress-fill {
      height: 100%; border-radius: 99px;
      background: linear-gradient(90deg, var(--green), #58d68d);
      transition: width .6s cubic-bezier(.4,0,.2,1);
    }
    .progress-fill.danger { background: linear-gradient(90deg, var(--red), #ff7875); }
    .progress-fill.warn { background: linear-gradient(90deg, var(--amber), #f0c040); }

    /* ── EXPENSE LIST ── */
    .expense-item {
      display: flex; align-items: center; gap: 12px;
      padding: 12px 0; border-bottom: 1px solid var(--border);
      animation: slideIn .25s ease;
    }
    .expense-item:last-child { border-bottom: none; }
    @keyframes slideIn { from { opacity:0; transform: translateX(-8px); } to { opacity:1; transform: none; } }
    .expense-cat-dot {
      width: 36px; height: 36px; border-radius: 10px;
      display: flex; align-items: center; justify-content: center;
      font-size: 1rem; flex-shrink: 0;
    }
    .expense-info { flex: 1; }
    .expense-info .name { font-weight: 500; font-size: .93rem; }
    .expense-info .cat { font-size: .75rem; color: var(--muted); }
    .expense-amount { font-weight: 600; color: var(--red); }
    .expense-delete {
      background: none; border: none; color: var(--muted);
      cursor: pointer; font-size: 1rem; padding: 4px;
      border-radius: 6px; transition: all .15s;
    }
    .expense-delete:hover { color: var(--red); background: var(--red-dim); }

    /* ── INCOME LIST ── */
    .income-item {
      display: flex; align-items: center; gap: 10px;
      padding: 10px 0; border-bottom: 1px solid var(--border);
      animation: slideIn .25s ease;
    }
    .income-item:last-child { border-bottom: none; }
    .income-amount { font-weight: 600; color: var(--green); margin-left: auto; }

    /* ── CHART BARS ── */
    .chart-wrap { padding: 8px 0; }
    .chart-row { display: flex; align-items: center; gap: 10px; margin-bottom: 10px; }
    .chart-row-label { width: 80px; font-size: .78rem; color: var(--muted); text-align: right; flex-shrink: 0; }
    .chart-bar-track { flex: 1; background: var(--bg); border-radius: 4px; height: 22px; overflow: hidden; }
    .chart-bar-fill {
      height: 100%; border-radius: 4px;
      background: linear-gradient(90deg, rgba(63,185,80,.5), rgba(63,185,80,.8));
      display: flex; align-items: center; padding-left: 8px;
      font-size: .74rem; color: var(--green); font-weight: 600;
      transition: width .6s cubic-bezier(.4,0,.2,1); min-width: 2px;
    }
    .chart-bar-fill.red-bar { background: linear-gradient(90deg, rgba(248,81,73,.4), rgba(248,81,73,.7)); color: var(--red); }

    /* ── BUDGET GOALS ── */
    .goal-item {
      display: flex; flex-direction: column; gap: 6px;
      padding: 14px 0; border-bottom: 1px solid var(--border);
    }
    .goal-item:last-child { border-bottom: none; }
    .goal-header { display: flex; justify-content: space-between; align-items: center; }
    .goal-name { font-weight: 500; font-size: .93rem; }
    .goal-pct { font-size: .8rem; color: var(--muted); }

    /* ── TIP BOX ── */
    .tip-box {
      border-radius: 10px; padding: 14px 18px;
      font-size: .88rem; display: flex; align-items: flex-start; gap: 10px;
      margin-top: 16px; animation: fadeIn .3s ease;
    }
    @keyframes fadeIn { from { opacity:0; } to { opacity:1; } }
    .tip-box.good { background: var(--green-dim); border: 1px solid rgba(63,185,80,.3); color: var(--green); }
    .tip-box.warn { background: var(--amber-dim); border: 1px solid rgba(210,153,34,.3); color: var(--amber); }
    .tip-box.bad { background: var(--red-dim); border: 1px solid rgba(248,81,73,.3); color: var(--red); }

    /* ── SAVINGS RATE RING ── */
    .ring-wrap { display: flex; align-items: center; gap: 24px; }
    .ring-svg { flex-shrink: 0; }
    .ring-info strong { font-size: 1.5rem; }
    .ring-info p { font-size: .82rem; color: var(--muted); }

    /* ── EMPTY STATE ── */
    .empty { text-align: center; padding: 28px 0; color: var(--muted); font-size: .88rem; }
    .empty span { font-size: 2rem; display: block; margin-bottom: 8px; opacity: .4; }

    /* ── SECTION SPACING ── */
    section { margin-bottom: 48px; }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--border);
      text-align: center; padding: 24px;
      color: var(--muted); font-size: .8rem;
    }
    footer a { color: var(--green); text-decoration: none; }
  </style>
</head>
<body>

<nav>
  <div class="nav-brand">Fin<span>Track</span></div>
  <ul class="nav-links">
    <li><a href="#dashboard">Dashboard</a></li>
    <li><a href="#income">Income</a></li>
    <li><a href="#expenses">Expenses</a></li>
    <li><a href="#budget">Budget</a></li>
  </ul>
</nav>

<!-- HERO -->
<div class="hero" id="top">
  <div class="hero-badge">🌿 Personal Finance Tracker</div>
  <h1>Take Control of<br><em>Your Money</em></h1>
  <p>Track income, manage expenses, and hit your savings goals — all in one clean dashboard.</p>
  <div class="hero-stats">
    <div class="hero-stat">
      <strong id="heroIncome">PKR 0</strong>
      <span>Total Income</span>
    </div>
    <div class="hero-stat">
      <strong id="heroExpense">PKR 0</strong>
      <span>Total Spent</span>
    </div>
    <div class="hero-stat">
      <strong id="heroSaved">0%</strong>
      <span>Savings Rate</span>
    </div>
  </div>
</div>

<main class="main">

  <!-- DASHBOARD METRICS -->
  <section id="dashboard">
    <div class="section-label">Overview</div>
    <div class="section-title">Financial Dashboard</div>
    <div class="grid-3">
      <div class="metric green-glow" data-icon="💰">
        <div class="label">Total Income</div>
        <div class="value" id="metricIncome" style="color:var(--green)">PKR 0</div>
        <div class="sub">This period</div>
      </div>
      <div class="metric red-glow" data-icon="💸">
        <div class="label">Total Expenses</div>
        <div class="value" id="metricExpense" style="color:var(--red)">PKR 0</div>
        <div class="sub">This period</div>
      </div>
      <div class="metric blue-glow" data-icon="🏦">
        <div class="label">Net Balance</div>
        <div class="value" id="metricBalance" style="color:var(--blue)">PKR 0</div>
        <div class="sub" id="metricBalanceSub">—</div>
      </div>
    </div>

    <!-- SAVINGS PROGRESS + RING -->
    <div class="grid-2">
      <div class="card">
        <h2><span class="icon" style="background:var(--green-dim)">📊</span> Spending Ratio</h2>
        <div class="progress-wrap">
          <div class="progress-label"><span>Expenses vs Income</span><span id="spendPct">0%</span></div>
          <div class="progress-track"><div class="progress-fill" id="spendBar" style="width:0%"></div></div>
        </div>
        <div class="progress-wrap">
          <div class="progress-label"><span>Savings Rate</span><span id="savePct">0%</span></div>
          <div class="progress-track"><div class="progress-fill" id="saveBar" style="width:0%"></div></div>
        </div>
        <div id="tipBox"></div>
      </div>

      <!-- CATEGORY BREAKDOWN CHART -->
      <div class="card">
        <h2><span class="icon" style="background:var(--surface2)">🗂️</span> Spending by Category</h2>
        <div class="chart-wrap" id="categoryChart">
          <div class="empty"><span>📂</span>Add expenses to see breakdown</div>
        </div>
      </div>
    </div>
  </section>

  <!-- INCOME SECTION -->
  <section id="income">
    <div class="section-label">Cash Flow</div>
    <div class="section-title">Income Sources</div>
    <div class="grid-2">
      <div class="card">
        <h2><span class="icon" style="background:var(--green-dim)">➕</span> Add Income</h2>
        <div class="field"><label>Description</label><input type="text" id="incomeDesc" placeholder="e.g. Monthly Salary"></div>
        <div class="field"><label>Amount (PKR)</label><input type="number" id="incomeAmount" placeholder="0" min="0"></div>
        <div class="field">
          <label>Source</label>
          <select id="incomeSource">
            <option value="Salary">💼 Salary</option>
            <option value="Freelance">🖥️ Freelance</option>
            <option value="Business">🏪 Business</option>
            <option value="Investment">📈 Investment</option>
            <option value="Other">📌 Other</option>
          </select>
        </div>
        <button class="btn btn-green" onclick="addIncome()">＋ Add Income</button>
      </div>

      <div class="card">
        <h2><span class="icon" style="background:var(--surface2)">📋</span> Income History</h2>
        <div id="incomeList"><div class="empty"><span>💼</span>No income added yet</div></div>
      </div>
    </div>
  </section>

  <!-- EXPENSES SECTION -->
  <section id="expenses">
    <div class="section-label">Spending</div>
    <div class="section-title">Expense Tracker</div>
    <div class="grid-2">
      <div class="card">
        <h2><span class="icon" style="background:var(--red-dim)">➖</span> Add Expense</h2>
        <div class="field"><label>Expense Name</label><input type="text" id="expenseName" placeholder="e.g. Groceries"></div>
        <div class="field"><label>Amount (PKR)</label><input type="number" id="expenseAmount" placeholder="0" min="0"></div>
        <div class="field">
          <label>Category</label>
          <select id="expenseCat">
            <option value="Food">🍔 Food & Dining</option>
            <option value="Transport">🚗 Transport</option>
            <option value="Shopping">🛍️ Shopping</option>
            <option value="Bills">⚡ Bills & Utilities</option>
            <option value="Health">💊 Health</option>
            <option value="Education">📚 Education</option>
            <option value="Entertainment">🎮 Entertainment</option>
            <option value="Other">📌 Other</option>
          </select>
        </div>
        <button class="btn btn-red" onclick="addExpense()">＋ Add Expense</button>
      </div>

      <div class="card">
        <h2><span class="icon" style="background:var(--surface2)">🧾</span> Expense Log</h2>
        <div id="expenseList"><div class="empty"><span>🧾</span>No expenses recorded yet</div></div>
      </div>
    </div>
  </section>

  <!-- BUDGET GOALS -->
  <section id="budget">
    <div class="section-label">Planning</div>
    <div class="section-title">Budget Goals</div>
    <div class="grid-2">
      <div class="card">
        <h2><span class="icon" style="background:var(--surface2)">🎯</span> Set Category Budget</h2>
        <div class="field">
          <label>Category</label>
          <select id="goalCat">
            <option value="Food">🍔 Food & Dining</option>
            <option value="Transport">🚗 Transport</option>
            <option value="Shopping">🛍️ Shopping</option>
            <option value="Bills">⚡ Bills & Utilities</option>
            <option value="Health">💊 Health</option>
            <option value="Education">📚 Education</option>
            <option value="Entertainment">🎮 Entertainment</option>
          </select>
        </div>
        <div class="field"><label>Monthly Limit (PKR)</label><input type="number" id="goalAmount" placeholder="e.g. 15000"></div>
        <button class="btn btn-ghost" onclick="addGoal()">🎯 Set Goal</button>
      </div>

      <div class="card">
        <h2><span class="icon" style="background:var(--surface2)">📏</span> Goal Progress</h2>
        <div id="goalList"><div class="empty"><span>🎯</span>No goals set yet</div></div>
      </div>
    </div>
  </section>

</main>

<footer>
  <p>FinTrack © 2025 &nbsp;·&nbsp; Plan Smart &nbsp;·&nbsp; Spend Better &nbsp;·&nbsp; <a href="#top">Back to top ↑</a></p>
</footer>

<script>
  const CAT_COLORS = {
    Food: '#f0883e', Transport: '#58a6ff', Shopping: '#d2a8ff',
    Bills: '#ffa657', Health: '#f85149', Education: '#79c0ff',
    Entertainment: '#bc8cff', Other: '#8b949e'
  };
  const CAT_EMOJI = {
    Food:'🍔', Transport:'🚗', Shopping:'🛍️', Bills:'⚡',
    Health:'💊', Education:'📚', Entertainment:'🎮', Other:'📌'
  };

  let totalIncome = 0, totalExpense = 0;
  let incomes = [], expenses = [], goals = {};

  function fmt(n) { return 'PKR ' + Math.abs(n).toLocaleString('en-PK'); }

  function addIncome() {
    const desc = document.getElementById('incomeDesc').value.trim();
    const amt  = parseFloat(document.getElementById('incomeAmount').value);
    const src  = document.getElementById('incomeSource').value;
    if (!desc || !amt || amt <= 0) return shake('incomeAmount');
    totalIncome += amt;
    incomes.push({ desc, amt, src });
    document.getElementById('incomeDesc').value = '';
    document.getElementById('incomeAmount').value = '';
    renderIncomeList(); updateAll();
  }

  function addExpense() {
    const name = document.getElementById('expenseName').value.trim();
    const amt  = parseFloat(document.getElementById('expenseAmount').value);
    const cat  = document.getElementById('expenseCat').value;
    if (!name || !amt || amt <= 0) return shake('expenseAmount');
    totalExpense += amt;
    expenses.push({ name, amt, cat, id: Date.now() });
    document.getElementById('expenseName').value = '';
    document.getElementById('expenseAmount').value = '';
    renderExpenseList(); updateAll();
  }

  function deleteExpense(id) {
    const idx = expenses.findIndex(e => e.id === id);
    if (idx < 0) return;
    totalExpense -= expenses[idx].amt;
    expenses.splice(idx, 1);
    renderExpenseList(); updateAll();
  }

  function addGoal() {
    const cat = document.getElementById('goalCat').value;
    const amt = parseFloat(document.getElementById('goalAmount').value);
    if (!amt || amt <= 0) return shake('goalAmount');
    goals[cat] = amt;
    document.getElementById('goalAmount').value = '';
    renderGoals(); updateAll();
  }

  function renderIncomeList() {
    const el = document.getElementById('incomeList');
    if (!incomes.length) { el.innerHTML = '<div class="empty"><span>💼</span>No income added yet</div>'; return; }
    el.innerHTML = incomes.map(i => `
      <div class="income-item">
        <div style="font-size:1.3rem">${i.src === 'Salary' ? '💼' : i.src === 'Freelance' ? '🖥️' : i.src === 'Business' ? '🏪' : i.src === 'Investment' ? '📈' : '📌'}</div>
        <div>
          <div style="font-weight:500;font-size:.93rem">${i.desc}</div>
          <div style="font-size:.75rem;color:var(--muted)">${i.src}</div>
        </div>
        <div class="income-amount">${fmt(i.amt)}</div>
      </div>`).join('');
  }

  function renderExpenseList() {
    const el = document.getElementById('expenseList');
    if (!expenses.length) { el.innerHTML = '<div class="empty"><span>🧾</span>No expenses recorded yet</div>'; return; }
    el.innerHTML = expenses.map(e => `
      <div class="expense-item">
        <div class="expense-cat-dot" style="background:${CAT_COLORS[e.cat]}22;color:${CAT_COLORS[e.cat]}">${CAT_EMOJI[e.cat]}</div>
        <div class="expense-info">
          <div class="name">${e.name}</div>
          <div class="cat">${e.cat}</div>
        </div>
        <div class="expense-amount">${fmt(e.amt)}</div>
        <button class="expense-delete" onclick="deleteExpense(${e.id})">✕</button>
      </div>`).join('');
  }

  function renderGoals() {
    const el = document.getElementById('goalList');
    if (!Object.keys(goals).length) { el.innerHTML = '<div class="empty"><span>🎯</span>No goals set yet</div>'; return; }
    el.innerHTML = Object.entries(goals).map(([cat, limit]) => {
      const spent = expenses.filter(e => e.cat === cat).reduce((s,e) => s + e.amt, 0);
      const pct = Math.min((spent / limit) * 100, 100);
      const cls = pct >= 90 ? 'danger' : pct >= 65 ? 'warn' : '';
      const col = pct >= 90 ? 'var(--red)' : pct >= 65 ? 'var(--amber)' : 'var(--green)';
      return `
        <div class="goal-item">
          <div class="goal-header">
            <span class="goal-name">${CAT_EMOJI[cat]} ${cat}</span>
            <span class="goal-pct" style="color:${col}">${Math.round(pct)}% — ${fmt(spent)} / ${fmt(limit)}</span>
          </div>
          <div class="progress-track">
            <div class="progress-fill ${cls}" style="width:${pct}%"></div>
          </div>
        </div>`;
    }).join('');
  }

  function renderCategoryChart() {
    const el = document.getElementById('categoryChart');
    if (!expenses.length) { el.innerHTML = '<div class="empty"><span>📂</span>Add expenses to see breakdown</div>'; return; }
    const totals = {};
    expenses.forEach(e => { totals[e.cat] = (totals[e.cat] || 0) + e.amt; });
    const max = Math.max(...Object.values(totals));
    el.innerHTML = Object.entries(totals)
      .sort((a,b) => b[1]-a[1])
      .map(([cat, val]) => `
        <div class="chart-row">
          <div class="chart-row-label">${CAT_EMOJI[cat]} ${cat}</div>
          <div class="chart-bar-track">
            <div class="chart-bar-fill red-bar" style="width:${(val/max)*100}%">${fmt(val)}</div>
          </div>
        </div>`).join('');
  }

  function updateAll() {
    const bal = totalIncome - totalExpense;
    const spendPct = totalIncome > 0 ? (totalExpense / totalIncome) * 100 : 0;
    const savePct  = totalIncome > 0 ? Math.max(0, (bal / totalIncome) * 100) : 0;

    // hero
    document.getElementById('heroIncome').textContent  = fmt(totalIncome);
    document.getElementById('heroExpense').textContent = fmt(totalExpense);
    document.getElementById('heroSaved').textContent   = Math.round(savePct) + '%';

    // metrics
    document.getElementById('metricIncome').textContent  = fmt(totalIncome);
    document.getElementById('metricExpense').textContent = fmt(totalExpense);
    document.getElementById('metricBalance').textContent = (bal < 0 ? '−' : '') + fmt(bal);
    document.getElementById('metricBalance').style.color = bal < 0 ? 'var(--red)' : 'var(--blue)';
    document.getElementById('metricBalanceSub').textContent =
      totalIncome === 0 ? '—' : bal >= 0 ? 'You are in surplus 🎉' : 'Deficit — review spending ⚠️';

    // bars
    const spendBar = document.getElementById('spendBar');
    const saveBar  = document.getElementById('saveBar');
    spendBar.style.width = Math.min(spendPct, 100) + '%';
    spendBar.className = 'progress-fill' + (spendPct > 80 ? ' danger' : spendPct > 60 ? ' warn' : '');
    saveBar.style.width = Math.min(savePct, 100) + '%';
    document.getElementById('spendPct').textContent = Math.round(spendPct) + '%';
    document.getElementById('savePct').textContent  = Math.round(savePct) + '%';

    // tip
    const tipEl = document.getElementById('tipBox');
    if (totalIncome === 0) { tipEl.innerHTML = ''; }
    else if (savePct >= 40) {
      tipEl.innerHTML = '<div class="tip-box good">✅ Excellent! You\'re saving ' + Math.round(savePct) + '% of your income. Keep it up!</div>';
    } else if (savePct >= 15) {
      tipEl.innerHTML = '<div class="tip-box warn">💡 You\'re saving ' + Math.round(savePct) + '%. Try to reach 30%+ for financial security.</div>';
    } else {
      tipEl.innerHTML = '<div class="tip-box bad">⚠️ Only ' + Math.round(savePct) + '% saved. Review your expenses and cut non-essentials.</div>';
    }

    renderCategoryChart();
    renderGoals();
  }

  function shake(id) {
    const el = document.getElementById(id);
    el.style.animation = 'none';
    el.style.borderColor = 'var(--red)';
    setTimeout(() => el.style.borderColor = '', 700);
  }
</script>
</body>
</html>
