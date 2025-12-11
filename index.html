<index.html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>財務規劃藍圖 (Pro)</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: { sans: ['Noto Sans TC', 'sans-serif'] },
                    boxShadow: {
                        'soft': '0 10px 40px -10px rgba(0,0,0,0.08)',
                        'glow': '0 0 20px rgba(85, 93, 169, 0.2)'
                    },
                    colors: {
                        ideal: { 
                            50: '#f7f7fa', text: '#6B6576', sub: '#A9A1B9', main: '#555DA9', hover: '#434a8a' 
                        },
                        real: { 50: '#fdf8f6', 500: '#ea580c', 600: '#c2410c' },
                        chart: { acc: '#7C8E7F', dec: '#CDB895', inf: '#9B3B3B' }
                    }
                }
            }
        }
    </script>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap" rel="stylesheet">
    
    <style>
        body { -webkit-tap-highlight-color: transparent; }
        input::-webkit-outer-spin-button, input::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; appearance: none; }
        input[type=range] { -webkit-appearance: none; appearance: none; background: transparent; cursor: pointer; }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none; appearance: none; height: 20px; width: 20px; border-radius: 50%;
            background: #555DA9; margin-top: -8px; border: 2px solid white; box-shadow: 0 2px 5px rgba(0,0,0,0.2); 
            transition: transform 0.1s, background-color 0.3s;
        }
        input[type=range]:active::-webkit-slider-thumb { transform: scale(1.1); }
        input[type=range]::-webkit-slider-runnable-track { width: 100%; height: 4px; background: #e2e8f0; border-radius: 99px; }
        .glass-panel {
            background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(10px); -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.6);
        }
        .theme-transition { transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1); }
        .fade-in { animation: fadeIn 0.4s ease-out; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }
        .modal-enter { opacity: 0; transform: scale(0.95); }
        .modal-enter-active { opacity: 1; transform: scale(1); transition: all 0.2s ease-out; }
    </style>
</head>
<body class="bg-ideal-50 text-ideal-text font-sans theme-transition" id="main-body">

    <div id="loading-screen" class="fixed inset-0 bg-white z-[99] flex items-center justify-center">
        <div class="flex flex-col items-center">
            <div class="animate-spin rounded-full h-8 w-8 border-b-2 border-ideal-main mb-2"></div>
            <p class="text-xs text-gray-400 tracking-widest uppercase">Initializing</p>
        </div>
    </div>

    <div id="app-container" class="hidden w-full max-w-[420px] mx-auto min-h-screen relative pb-10 shadow-2xl bg-white border-x border-gray-100">
        
        <header id="header-bg" class="bg-ideal-main text-white pt-10 pb-20 px-8 rounded-b-[2.5rem] shadow-lg relative overflow-hidden z-0 theme-transition">
            <div class="absolute top-[-20%] right-[-10%] w-64 h-64 rounded-full bg-white opacity-10 blur-3xl"></div>
            <div class="relative z-10 text-center">
                <h1 class="text-2xl font-bold tracking-wide drop-shadow-sm">財務規劃藍圖</h1>
                <p class="text-white/80 text-xs font-light tracking-wider mt-2 uppercase">Retirement Simulator</p>
            </div>
        </header>

        <div class="px-5 -mt-14 relative z-10">
            <div class="glass-panel rounded-3xl shadow-soft p-6 space-y-6">
                
                <div class="grid grid-cols-2 gap-4">
                    <div class="space-y-1">
                        <label class="text-[10px] font-bold text-ideal-sub uppercase tracking-wider ml-1">目前年齡</label>
                        <input type="text" inputmode="decimal" id="age-current" value="30" class="input-field w-full bg-gray-50 border border-gray-200 rounded-xl px-2 py-2.5 text-center text-base font-bold text-ideal-text focus:outline-none focus:ring-2 focus:ring-ideal-main focus:bg-white transition-all shadow-sm" onblur="handleInputBlur(this)" onfocus="handleInputFocus(this)">
                    </div>
                    <div class="space-y-1">
                        <label class="text-[10px] font-bold text-ideal-sub uppercase tracking-wider ml-1">距離退休</label>
                        <input type="text" inputmode="decimal" id="years-to-retire" value="35" class="input-field w-full bg-gray-50 border border-gray-200 rounded-xl px-2 py-2.5 text-center text-base font-bold text-ideal-text focus:outline-none focus:ring-2 focus:ring-ideal-main focus:bg-white transition-all shadow-sm" onblur="handleInputBlur(this)" onfocus="handleInputFocus(this)">
                    </div>
                </div>

                <div class="space-y-2">
                    <label class="text-[10px] font-bold text-ideal-sub uppercase tracking-wider ml-1">初始本金 (萬)</label>
                    <div class="relative">
                        <input type="text" inputmode="decimal" id="principal" value="100" class="input-field w-full bg-gray-50 border border-gray-200 rounded-xl pl-4 pr-10 py-2.5 text-right text-lg font-bold text-ideal-text focus:outline-none focus:ring-2 focus:ring-ideal-main focus:bg-white transition-all shadow-sm" onblur="handleInputBlur(this)" onfocus="handleInputFocus(this)">
                        <span class="absolute right-4 top-1/2 -translate-y-1/2 text-ideal-sub text-xs font-medium">萬</span>
                    </div>
                </div>

                <div class="space-y-2 pt-1">
                    <div class="flex justify-between items-end">
                        <label class="text-xs font-bold text-ideal-text flex items-center gap-1">
                            每月定期投入
                            <button onclick="openModal('monthly')" class="text-ideal-sub hover:text-ideal-main transition-colors icon-btn"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4"><path d="M12 2C7.58 2 4 5.58 4 10c0 2.03.69 3.9 1.85 5.4.11.14.15.32.15.5v3.1c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-3.1c0-.18.04-.36.15-.5C19.31 13.9 20 12.03 20 10c0-4.42-3.58-8-8-8zm1 16h-2v-1h2v1zm0-2h-2v-1h2v1zm-1-12c3.31 0 6 2.69 6 6 0 1.94-1.05 3.65-2.63 4.63-.35.22-.57.6-.57 1.02V17h-2.8v-1.35c0-.42-.22-.8-.57-1.02C6.05 13.65 5 11.94 5 10c0-3.31 2.69-6 6-6z"/></svg></button>
                        </label>
                        <div class="text-lg font-bold text-ideal-main tracking-tight flex items-baseline gap-1 theme-text">
                            <span class="text-xs text-gray-400 font-normal">$</span>
                            <input type="text" id="monthly-invest" value="20,000" class="bg-transparent text-right w-24 focus:outline-none border-b border-dashed border-gray-300 focus:border-ideal-main transition-colors" onblur="handleInputBlur(this)" onfocus="handleInputFocus(this)">
                        </div>
                    </div>
                    <input type="range" id="slider-monthly" min="0" max="100000" step="1000" value="20000" class="w-full text-ideal-main cursor-pointer slider-input" oninput="syncSlider('monthly-invest', this.value)">
                </div>

                <div class="space-y-2">
                    <div class="flex justify-between items-end">
                        <label class="text-xs font-bold text-ideal-text flex items-center gap-1">
                            年化報酬率
                            <button onclick="openModal('roi')" class="text-ideal-sub hover:text-ideal-main transition-colors icon-btn"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4"><path d="M12 2C7.58 2 4 5.58 4 10c0 2.03.69 3.9 1.85 5.4.11.14.15.32.15.5v3.1c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-3.1c0-.18.04-.36.15-.5C19.31 13.9 20 12.03 20 10c0-4.42-3.58-8-8-8zm1 16h-2v-1h2v1zm0-2h-2v-1h2v1zm-1-12c3.31 0 6 2.69 6 6 0 1.94-1.05 3.65-2.63 4.63-.35.22-.57.6-.57 1.02V17h-2.8v-1.35c0-.42-.22-.8-.57-1.02C6.05 13.65 5 11.94 5 10c0-3.31 2.69-6 6-6z"/></svg></button>
                        </label>
                        <div class="text-lg font-bold text-ideal-main tracking-tight flex items-baseline gap-1 theme-text">
                            <input type="number" id="roi-input" value="6" step="0.5" class="bg-transparent text-right w-16 focus:outline-none border-b border-dashed border-gray-300 focus:border-ideal-main transition-colors font-mono" oninput="syncRoiSlider(this.value)">
                            <span class="text-xs text-gray-400 font-normal">%</span>
                        </div>
                    </div>
                    <input type="range" id="slider-roi" min="1" max="15" step="0.5" value="6" class="w-full text-ideal-main cursor-pointer slider-input" oninput="syncRoiInput(this.value)">
                </div>

                <div class="space-y-2 pb-2">
                    <div class="flex justify-between items-end">
                        <label class="text-xs font-bold text-ideal-text">退休後每月提領</label>
                        <div class="text-lg font-bold text-ideal-text tracking-tight flex items-baseline gap-1">
                            <span class="text-xs text-gray-400 font-normal">$</span>
                            <input type="text" id="monthly-withdraw" value="50,000" class="bg-transparent text-right w-24 focus:outline-none border-b border-dashed border-gray-300 focus:border-ideal-main transition-colors" onblur="handleInputBlur(this)" onfocus="handleInputFocus(this)">
                        </div>
                    </div>
                    <input type="range" id="slider-withdraw" min="10000" max="200000" step="5000" value="50000" class="w-full text-ideal-main cursor-pointer slider-input" oninput="syncSlider('monthly-withdraw', this.value)">
                </div>

                <hr class="border-gray-100 border-dashed">

                <div id="result-bar" class="bg-ideal-main rounded-2xl p-5 text-center text-white shadow-lg transform transition-transform hover:scale-[1.02] theme-transition">
                    <p class="text-[10px] opacity-80 mb-1 font-medium tracking-widest uppercase">退休日已累積資產</p>
                    <p id="result-asset" class="text-2xl font-bold tracking-tight drop-shadow-md">$0</p>
                </div>

                <div id="conclusion-box" class="p-4 rounded-xl text-sm font-bold text-center bg-green-50 text-green-700 border border-green-200 leading-loose">
                    計算中...
                </div>

                <div class="h-64 w-full relative">
                    <canvas id="financeChart"></canvas>
                </div>

                <div class="flex items-center justify-between bg-gray-50 p-4 rounded-xl border border-gray-100">
                    <div class="flex items-center gap-3">
                        <div class="relative flex items-center">
                            <input type="checkbox" id="check-inflation" class="peer h-5 w-5 cursor-pointer appearance-none rounded border border-gray-300 shadow-sm transition-all checked:border-ideal-main checked:bg-ideal-main hover:border-ideal-main" onchange="toggleInflationMode()">
                            <svg class="pointer-events-none absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 text-white opacity-0 peer-checked:opacity-100" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="4" stroke-linecap="round" stroke-linejoin="round" width="12" height="12"><polyline points="20 6 9 17 4 12"></polyline></svg>
                        </div>
                        <div class="flex flex-col">
                            <div class="flex items-center gap-2">
                                <span class="text-sm font-bold text-gray-700">考慮通貨膨脹</span>
                                <button onclick="openModal('inflation')" class="text-gray-400 hover:text-gray-600"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-3 h-3"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg></button>
                            </div>
                            <div id="inflation-input-group" class="hidden mt-1 flex items-center gap-2 fade-in">
                                <span class="text-[10px] text-gray-500">預估年通膨率</span>
                                <input type="number" id="inflation-rate" value="2.5" step="0.1" class="w-12 bg-white border border-gray-300 rounded px-1 py-0.5 text-right text-xs font-bold focus:outline-none focus:border-real-500" oninput="calc()">
                                <span class="text-[10px] text-gray-500">%</span>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
            
            <footer class="mt-8 mb-4 px-4 text-center opacity-60">
                <p class="text-[10px] text-ideal-sub leading-relaxed font-light">
                    本試算僅供參考，不代表未來報酬保證。<br>
                    投資有風險，請審慎評估。<br>
                    Professional Planner
                </p>
            </footer>
        </div>
    </div>

    <div id="info-modal" class="fixed inset-0 z-[100] hidden" role="dialog" aria-modal="true">
        <div class="fixed inset-0 bg-gray-900/40 backdrop-blur-sm transition-opacity" onclick="closeModal()"></div>
        <div class="fixed inset-0 z-10 overflow-y-auto pointer-events-none">
            <div class="flex min-h-full items-center justify-center p-4 text-center">
                <div id="modal-card" class="pointer-events-auto relative transform rounded-2xl bg-white text-left shadow-2xl w-full max-w-sm p-6 border border-gray-100 modal-enter transition-all">
                    <button type="button" class="absolute top-4 right-4 text-gray-400 hover:text-gray-600 focus:outline-none p-1 transition-colors" onclick="closeModal()">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" /></svg>
                    </button>
                    <div class="flex items-center gap-3 mb-4 pr-8">
                        <div class="text-ideal-main icon-btn">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6"><path d="M12 2C7.58 2 4 5.58 4 10c0 2.03.69 3.9 1.85 5.4.11.14.15.32.15.5v3.1c0 .55.45 1 1 1h10c.55 0 1-.45 1-1v-3.1c0-.18.04-.36.15-.5C19.31 13.9 20 12.03 20 10c0-4.42-3.58-8-8-8zm0 14c-2.33 0-4.32-1.45-5.12-3.5h1.67c.7 1.18 1.96 2 3.45 2s2.75-.82 3.45-2h1.67c-.8 2.05-2.79 3.5-5.12 3.5z"/></svg>
                        </div>
                        <h3 class="text-lg font-bold text-ideal-text tracking-tight" id="modal-title">...</h3>
                    </div>
                    <div class="text-sm text-ideal-text leading-relaxed space-y-4" id="modal-content"></div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // 設定 Gist URL (若需啟用遙控開關功能請填入)
        const CONFIG_URL = 'YOUR_GIST_RAW_URL_HERE'; 

        window.onload = function() {
            setTimeout(() => {
                if(CONFIG_URL.includes('YOUR_GIST')) initApp();
                else {
                    fetch(CONFIG_URL + '?t=' + new Date().getTime())
                        .then(res => res.json())
                        .then(data => data.active ? initApp() : showBlocked(data.message))
                        .catch(() => initApp());
                }
            }, 600);
        };

        function initApp() {
            document.getElementById('loading-screen').classList.add('hidden');
            document.getElementById('app-container').classList.remove('hidden');
            updateThemeColor(); // 確保初始顏色正確
            calc(); 
        }

        function showBlocked(msg) {
            document.getElementById('loading-screen').innerHTML = `<div class="p-8 text-center"><h1 class="text-2xl font-bold mb-4 text-gray-800">服務維護中</h1><p class="text-gray-500">${msg || '請稍後再試'}</p></div>`;
        }

        // Tools
        function parseRaw(str) { if(!str) return 0; return parseFloat(str.toString().replace(/,/g, '')) || 0; }
        function formatMoney(num) { return Math.round(num).toLocaleString('en-US'); }
        function handleInputBlur(el) { el.value = formatMoney(parseRaw(el.value)); calc(); }
        function handleInputFocus(el) { let val = parseRaw(el.value); if(val!==0) el.value = val; el.select(); }
        
        // 滑桿同步
        function syncSlider(inputId, val) { 
            document.getElementById(inputId).value = formatMoney(val); 
            calc(); 
        }
        
        // ROI 雙向綁定
        function syncRoiInput(val) {
            document.getElementById('roi-input').value = val;
            calc();
        }
        function syncRoiSlider(val) {
            document.getElementById('slider-roi').value = val;
            calc();
        }

        // Logic
        let chartInstance = null;
        let isInflationMode = false;

        function toggleInflationMode() {
            isInflationMode = document.getElementById('check-inflation').checked;
            const inputGroup = document.getElementById('inflation-input-group');
            isInflationMode ? inputGroup.classList.remove('hidden') : inputGroup.classList.add('hidden');
            updateThemeColor();
            calc();
        }

        function updateThemeColor() {
            const header = document.getElementById('header-bg');
            const resultBar = document.getElementById('result-bar');
            
            const els = {
                slider: document.querySelectorAll('.slider-input'),
                themeText: document.querySelectorAll('.theme-text'),
                iconBtn: document.querySelectorAll('.icon-btn'),
                inputFocus: document.querySelectorAll('.input-field')
            };

            if (isInflationMode) {
                // Real Mode (褐色系)
                header.className = "bg-gradient-to-br from-real-500 to-real-600 text-white pt-10 pb-20 px-8 rounded-b-[2.5rem] shadow-lg relative overflow-hidden z-0 theme-transition";
                resultBar.className = "bg-real-500 rounded-2xl p-5 text-center text-white shadow-lg transform transition-transform hover:scale-[1.02] theme-transition";
                
                // 滑桿點點變色
                document.querySelectorAll('input[type=range]').forEach(el => {
                    el.style.color = '#c2410c'; // real-600
                });

                els.themeText.forEach(el => el.classList.replace('text-ideal-main', 'text-real-600'));
                els.iconBtn.forEach(el => el.classList.replace('text-ideal-sub', 'text-real-600'));
                els.iconBtn.forEach(el => el.classList.replace('text-ideal-main', 'text-real-600')); // Modal icon
                els.inputFocus.forEach(el => el.classList.replace('focus:ring-ideal-main', 'focus:ring-real-500'));
            } else {
                // Ideal Mode (莫蘭迪紫)
                header.className = "bg-ideal-main text-white pt-10 pb-20 px-8 rounded-b-[2.5rem] shadow-lg relative overflow-hidden z-0 theme-transition";
                resultBar.className = "bg-ideal-main rounded-2xl p-5 text-center text-white shadow-lg transform transition-transform hover:scale-[1.02] theme-transition";
                
                // 滑桿點點變色
                document.querySelectorAll('input[type=range]').forEach(el => {
                    el.style.color = '#555DA9'; // ideal-main
                });

                els.themeText.forEach(el => el.classList.replace('text-real-600', 'text-ideal-main'));
                els.iconBtn.forEach(el => el.classList.replace('text-real-600', 'text-ideal-sub'));
                els.iconBtn.forEach(el => el.classList.replace('text-real-600', 'text-ideal-main'));
                els.inputFocus.forEach(el => el.classList.replace('focus:ring-real-500', 'focus:ring-ideal-main'));
            }
        }

        function calc() {
            const ageCurrent = parseRaw(document.getElementById('age-current').value);
            const yearsToRetire = parseRaw(document.getElementById('years-to-retire').value);
            const principal = parseRaw(document.getElementById('principal').value) * 10000;
            const monthlyInvest = parseRaw(document.getElementById('monthly-invest').value);
            // 改為讀取 slider (因為 slider 和 input 是同步的，讀 slider 比較保險)
            const roi = parseFloat(document.getElementById('slider-roi').value) / 100;
            const monthlyWithdrawRaw = parseRaw(document.getElementById('monthly-withdraw').value);
            const inflationRate = isInflationMode ? (parseFloat(document.getElementById('inflation-rate').value) || 0) / 100 : 0;
            
            const ageRetire = ageCurrent + yearsToRetire;
            const maxAge = 95;

            let labels = [];
            let dataAccumulate = []; // 綠
            let dataDecumulate = []; // 金
            let dataReal = [];       // 紅線
            
            let currentAsset = principal;
            let discountFactor = 1;

            // 1. 累積期
            for (let i = 0; i <= yearsToRetire; i++) {
                labels.push((ageCurrent + i));
                dataAccumulate.push(currentAsset);
                dataDecumulate.push(null); 
                dataReal.push(currentAsset / discountFactor);

                currentAsset = currentAsset * (1 + roi) + (monthlyInvest * 12);
                if(isInflationMode) discountFactor *= (1 + inflationRate);
            }

            // 更新介面大字
            const assetAtRetirement = dataAccumulate[dataAccumulate.length - 1];
            document.getElementById('result-asset').textContent = '$' + formatMoney(assetAtRetirement);

            // 2. 提領期
            let yearsInRetirement = maxAge - ageRetire;
            let yearlyWithdraw = monthlyWithdrawRaw * 12;
            if (isInflationMode) yearlyWithdraw *= Math.pow(1 + inflationRate, yearsToRetire);

            let depletedAge = null;

            for (let i = 1; i <= yearsInRetirement; i++) {
                labels.push((ageRetire + i));
                
                currentAsset = currentAsset * (1 + roi) - yearlyWithdraw;
                
                if (isInflationMode) {
                    yearlyWithdraw *= (1 + inflationRate);
                    discountFactor *= (1 + inflationRate);
                }
                
                dataAccumulate.push(null);

                if (currentAsset > 0) {
                    dataDecumulate.push(currentAsset);
                    dataReal.push(currentAsset / discountFactor);
                } else {
                    dataDecumulate.push(0);
                    dataReal.push(0);
                    if (!depletedAge) depletedAge = ageRetire + i;
                }
            }

            updateConclusion(depletedAge, currentAsset);
            drawChart(labels, dataAccumulate, dataDecumulate, dataReal, ageRetire);
        }

        function updateConclusion(depletedAge, finalAsset) {
            const box = document.getElementById('conclusion-box');
            if (depletedAge) {
                box.className = "p-5 rounded-xl text-sm font-bold text-center bg-red-50 text-red-700 border border-red-200 leading-loose";
                box.innerHTML = `⚠️ <span class="text-lg">風險警示</span><br>資產預計將在 <span class="text-2xl border-b-2 border-red-300">${depletedAge}歲</span> 用盡`;
            } else {
                box.className = "p-5 rounded-xl text-sm font-bold text-center bg-green-50 text-green-700 border border-green-200 leading-loose";
                box.innerHTML = `🎉 <span class="text-lg">恭喜！</span><br>95歲資產剩餘：<br><span class="text-3xl tracking-tight">$${formatMoney(finalAsset)}</span>`;
            }
        }

        function drawChart(labels, dataAccumulate, dataDecumulate, dataReal, retireAge) {
            const ctx = document.getElementById('financeChart').getContext('2d');
            if (chartInstance) chartInstance.destroy();

            const datasets = [
                // 1. 累積期 (莫蘭迪綠)
                {
                    type: 'bar',
                    label: '累積資產',
                    data: dataAccumulate,
                    backgroundColor: '#7C8E7F', 
                    barPercentage: 1.0, 
                    categoryPercentage: 1.0,
                    order: 3
                },
                // 2. 提領期 (燕麥金)
                {
                    type: 'bar',
                    label: '提領資產',
                    data: dataDecumulate,
                    backgroundColor: '#CDB895',
                    barPercentage: 1.0,
                    categoryPercentage: 1.0,
                    order: 2
                }
            ];

            // 3. 通膨折線
            if (isInflationMode) {
                datasets.push({
                    type: 'line',
                    label: '實質購買力',
                    data: dataReal,
                    borderColor: '#9B3B3B',
                    borderWidth: 2,
                    pointRadius: 0,
                    fill: false,
                    tension: 0.4,
                    order: 1
                });
            }

            chartInstance = new Chart(ctx, {
                data: { labels: labels, datasets: datasets },
                options: {
                    responsive: true, maintainAspectRatio: false,
                    interaction: { mode: 'index', intersect: false },
                    plugins: {
                        legend: { display: false }, 
                        tooltip: { 
                            callbacks: { label: c => ' ' + c.dataset.label + ': $' + formatMoney(c.raw) } 
                        }
                    },
                    scales: {
                        x: { 
                            grid: { display: false }, 
                            ticks: { 
                                maxTicksLimit: 8, font: {size:10, family: "'Noto Sans TC'"},
                                callback: function(val, index) {
                                    const age = this.getLabelForValue(val);
                                    if(age == retireAge) return [age + '歲', '退休日'];
                                    return age + '歲';
                                },
                                font: function(context) {
                                    const age = context.chart.data.labels[context.index];
                                    if (age == retireAge) return { weight: 'bold', size: 10 };
                                    return { weight: 'normal', size: 10 };
                                }
                            } 
                        },
                        y: { display: false }
                    }
                }
            });
        }

        const modalData = {
            'monthly': { title: '每月定期投入', content: `<p>扣除生活開銷與房貸後的閒置資金。</p><div class="bg-yellow-50 p-3 rounded-lg border border-yellow-100 mt-2"><p class="font-bold text-yellow-800 text-xs mb-1">💡 專家建議：</p><p class="text-xs text-yellow-700">請先預留 3-6 個月的緊急預備金。</p></div>` },
            'roi': { title: '年化報酬率 (%)', content: `<p>投資組合長期的幾何平均年成長率。</p><p class="font-bold text-gray-800 mt-3 mb-2">📊 參考數據：</p><ul class="space-y-2"><li class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-green-500"></span><span><strong>保守 (債券)：</strong>3% ~ 4%</span></li><li class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-blue-500"></span><span><strong>穩健 (股債)：</strong>5% ~ 6%</span></li><li class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-purple-500"></span><span><strong>積極 (股票)：</strong>7% ~ 9%</span></li></ul>` },
            'inflation': { title: '通貨膨脹影響', content: `<p>物價上漲導致貨幣「購買力」下降。</p><p class="font-bold text-gray-800 mt-3">勾選後：</p><ul class="list-disc pl-5 space-y-1 mt-1"><li><strong class="text-red-700">紅折線：</strong>扣除通膨後的真實價值。</li><li><strong>提領變多：</strong>退休時所需生活費大幅增加。</li></ul>` }
        };

        function openModal(key) {
            const data = modalData[key];
            if(data) {
                document.getElementById('modal-title').innerHTML = data.title;
                document.getElementById('modal-content').innerHTML = data.content;
                const modal = document.getElementById('info-modal');
                const card = document.getElementById('modal-card');
                modal.classList.remove('hidden');
                setTimeout(() => { card.classList.remove('modal-enter'); card.classList.add('modal-enter-active'); }, 10);
            }
        }
        function closeModal() {
            const modal = document.getElementById('info-modal');
            const card = document.getElementById('modal-card');
            card.classList.remove('modal-enter-active');
            setTimeout(() => { modal.classList.add('hidden'); card.classList.add('modal-enter'); }, 200);
        }
    </script>
</body>
</html>