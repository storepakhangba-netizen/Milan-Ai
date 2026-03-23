<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <title>MAXXI AI</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: { sans: ['-apple-system', 'BlinkMacSystemFont', 'sans-serif'], },
                    colors: {
                        ios: { bg: '#030305', surface: 'rgba(24, 24, 27, 0.65)', blue: '#2563EB', text: '#FFFFFF', border: 'rgba(255, 255, 255, 0.08)' }
                    },
                    animation: {
                        'spring-up': 'springUp 0.8s cubic-bezier(0.16, 1, 0.3, 1) forwards',
                        'bubble-pop': 'bubblePop 0.5s cubic-bezier(0.16, 1, 0.3, 1) forwards',
                        'orb-float': 'orbFloat 20s ease-in-out infinite alternate',
                    },
                    keyframes: {
                        springUp: { '0%': { opacity: '0', transform: 'translateY(40px) scale(0.95)' }, '100%': { opacity: '1', transform: 'translateY(0) scale(1)' } },
                        bubblePop: { '0%': { opacity: '0', transform: 'scale(0.95) translateY(15px)' }, '100%': { opacity: '1', transform: 'scale(1) translateY(0)' } },
                        orbFloat: { '0%': { transform: 'translate(0, 0) scale(1)' }, '50%': { transform: 'translate(40px, -40px) scale(1.1)' }, '100%': { transform: 'translate(-20px, 30px) scale(0.95)' } }
                    }
                }
            }
        }
    </script>

    <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/atom-one-dark.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        /* Base Reset */
        html, body { -webkit-tap-highlight-color: transparent; scroll-behavior: smooth; background-color: #030305; overscroll-behavior-y: none; color: #FFFFFF; }
        .h-screen-fix { height: 100vh; height: 100dvh; }
        ::-webkit-scrollbar { width: 0px; background: transparent; }
        
        /* 🌌 Stunning Ambient Background Glows */
        .bg-mesh-container { position: fixed; inset: 0; z-index: 0; overflow: hidden; pointer-events: none; background-color: #030305; background-image: radial-gradient(rgba(255, 255, 255, 0.02) 1px, transparent 1px); background-size: 24px 24px; }
        .orb { position: absolute; border-radius: 50%; filter: blur(90px); opacity: 0.45; }
        .orb-1 { top: -15%; left: -10%; width: 60vw; height: 60vw; background: #1E3A8A; animation: orbFloat 25s infinite alternate ease-in-out; }
        .orb-2 { bottom: -20%; right: -10%; width: 70vw; height: 70vw; background: #4C1D95; animation: orbFloat 20s infinite alternate-reverse ease-in-out; }
        .orb-3 { top: 30%; left: 40%; width: 50vw; height: 50vw; background: #0F766E; animation: orbFloat 30s infinite alternate ease-in-out; opacity: 0.3; }

        /* 🔲 Premium Glass Effects */
        .glass-heavy { background: rgba(5, 5, 8, 0.6); backdrop-filter: blur(40px) saturate(200%); -webkit-backdrop-filter: blur(40px) saturate(200%); border-bottom: 1px solid rgba(255, 255, 255, 0.05); }
        .glass-sidebar { background: rgba(5, 5, 8, 0.8); backdrop-filter: blur(40px) saturate(200%); border-right: 1px solid rgba(255, 255, 255, 0.05); }
        .glass-input { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(35px) saturate(180%); border: 1px solid rgba(255, 255, 255, 0.08); box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5), inset 0 1px 2px rgba(255,255,255,0.05); }
        .glass-card { background: linear-gradient(145deg, rgba(255,255,255,0.06) 0%, rgba(255,255,255,0.01) 100%); backdrop-filter: blur(20px); border: 1px solid rgba(255, 255, 255, 0.05); transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1); }
        .glass-card:hover { background: rgba(255,255,255,0.09); box-shadow: 0 15px 35px rgba(37, 99, 235, 0.15); transform: translateY(-3px); }

        /* Typography & Markdown */
        .markdown-body { font-size: 1.05rem; line-height: 1.6; word-wrap: break-word; color: #E5E7EB; }
        .markdown-body p { margin-bottom: 0.85em; } .markdown-body p:last-child { margin-bottom: 0; }
        .markdown-body :not(pre) > code { background-color: rgba(255, 255, 255, 0.1); padding: 0.2em 0.4em; border-radius: 6px; font-size: 0.85em; color: #93C5FD; }
        .markdown-body pre { margin: 0; padding: 1.2rem; overflow-x: auto; background: transparent !important; }
        .markdown-body pre code { font-size: 0.9em; background: transparent; padding: 0; color: #E5E7EB; }
        .markdown-body a { color: #60A5FA; text-decoration: underline; text-underline-offset: 2px; }
        .markdown-body strong { font-weight: 600; color: #FFFFFF; }
        .code-block-wrapper { background: rgba(0,0,0,0.5); border: 1px solid rgba(255,255,255,0.08); border-radius: 16px; overflow: hidden; margin: 1.2em 0; backdrop-filter: blur(10px); }
        .code-header { display: flex; justify-content: space-between; align-items: center; background: rgba(255,255,255,0.04); padding: 8px 16px; border-bottom: 1px solid rgba(255,255,255,0.05); font-size: 0.75rem; color: #A1A1AA; font-family: monospace; text-transform: uppercase; }

        /* Typing Dots */
        .typing-indicator { display: inline-flex; align-items: center; gap: 5px; padding: 6px 4px; }
        .typing-dot { animation: typingBounce 1.4s infinite ease-in-out both; width: 6px; height: 6px; border-radius: 50%; background-color: #60A5FA; }
        .typing-dot:nth-child(1) { animation-delay: -0.32s; } .typing-dot:nth-child(2) { animation-delay: -0.16s; }
        @keyframes typingBounce { 0%, 80%, 100% { transform: translateY(0) scale(0.8); opacity: 0.3; } 40% { transform: translateY(-5px) scale(1.1); opacity: 1; box-shadow: 0 0 10px rgba(96, 165, 250, 0.6); } }
        
        /* 🤖 Custom MAXXI Avatar */
        .maxxi-avatar { background: linear-gradient(135deg, #1E3A8A 0%, #2563EB 100%); box-shadow: 0 0 20px rgba(37,99,235,0.4), inset 0 2px 5px rgba(255,255,255,0.3); position: relative; display: flex; align-items: center; justify-content: center; flex-direction: column; }
        .maxxi-eyes { display: flex; gap: 5px; margin-top: 2px; }
        .maxxi-eye { width: 5px; height: 5px; background-color: white; border-radius: 50%; box-shadow: 0 0 5px rgba(255,255,255,0.8); }
        .maxxi-smile { width: 10px; height: 3px; border-bottom: 2px solid white; border-radius: 50%; margin-top: 3px; filter: drop-shadow(0 0 2px rgba(255,255,255,0.5)); }

        textarea { -webkit-appearance: none; appearance: none; }
    </style>
</head>
<body class="bg-[#030305] text-white antialiased overflow-hidden">

    <div class="bg-mesh-container">
        <div class="orb orb-1"></div>
        <div class="orb orb-2"></div>
        <div class="orb orb-3"></div>
    </div>

    <div id="loading" class="fixed inset-0 z-[100] flex flex-col items-center justify-center bg-[#030305] transition-opacity duration-500">
        <div class="maxxi-avatar w-16 h-16 rounded-[18px] mb-6 animate-pulse">
            <div class="maxxi-eyes"><div class="maxxi-eye" style="width:7px; height:7px;"></div><div class="maxxi-eye" style="width:7px; height:7px;"></div></div>
            <div class="maxxi-smile" style="width:14px; border-width: 3px; margin-top: 5px;"></div>
        </div>
        <div class="text-[#2563EB] text-[11px] font-bold tracking-[0.3em] uppercase drop-shadow-[0_0_10px_rgba(37,99,235,0.6)]">Loading MAXXI</div>
    </div>

    <div id="app" class="flex h-screen-fix w-full relative hidden opacity-0 transition-opacity duration-700 z-10">
        
        <div id="sidebar-overlay" class="fixed inset-0 bg-black/60 backdrop-blur-sm z-40 hidden md:hidden transition-opacity duration-400 opacity-0"></div>

        <aside id="sidebar" class="fixed inset-y-0 left-0 z-50 w-[290px] glass-sidebar transform -translate-x-full md:translate-x-0 transition-transform duration-500 md:relative flex flex-col h-full shadow-[20px_0_40px_rgba(0,0,0,0.5)] md:shadow-none">
            <div class="pt-12 pb-4 px-5 flex items-center justify-between border-b border-[rgba(255,255,255,0.05)]">
                <div class="flex items-center gap-3">
                    <div class="maxxi-avatar w-8 h-8 rounded-[10px] shadow-none">
                        <div class="maxxi-eyes"><div class="maxxi-eye" style="width:4px;height:4px;"></div><div class="maxxi-eye" style="width:4px;height:4px;"></div></div>
                        <div class="maxxi-smile" style="width:6px; margin-top:1px;"></div>
                    </div>
                    <h2 class="text-[19px] font-semibold tracking-tight text-white drop-shadow-md">MAXXI AI</h2>
                </div>
                <button id="close-sidebar-btn" class="md:hidden text-[#A1A1AA] hover:text-white p-2 transition-colors">
                    <i class="fas fa-times text-lg"></i>
                </button>
            </div>
            
            <div class="p-4 pb-2">
                <button id="new-chat-btn" class="w-full flex items-center justify-center gap-2 bg-gradient-to-r from-[#2563EB] to-[#3B82F6] hover:opacity-90 text-white text-[15px] font-medium py-3.5 rounded-[14px] transition-all active:scale-[0.97] shadow-[0_0_20px_rgba(37,99,235,0.4)] mb-4">
                    <i class="fas fa-plus"></i> New Chat
                </button>
                
                <div class="relative group">
                    <i class="fas fa-search absolute left-3.5 top-1/2 transform -translate-y-1/2 text-[#A1A1AA] text-sm transition-colors group-focus-within:text-[#3B82F6]"></i>
                    <input type="text" id="chat-search" class="w-full bg-[rgba(255,255,255,0.03)] border border-[rgba(255,255,255,0.08)] rounded-[14px] pl-10 pr-3 py-3 text-[14px] text-white placeholder-[#A1A1AA] outline-none focus:border-[#3B82F6] focus:bg-[rgba(255,255,255,0.06)] transition-all" placeholder="Search history...">
                </div>
            </div>

            <div class="flex-1 overflow-y-auto px-3 pb-4 space-y-1 mt-1" id="chat-history-list"></div>
            
            <div class="p-4 border-t border-[rgba(255,255,255,0.05)] bg-[rgba(0,0,0,0.2)]">
                <button id="open-admin-btn" class="w-full flex items-center justify-center gap-3 px-3 py-3.5 text-[14px] font-medium text-[#A1A1AA] hover:text-white hover:bg-[rgba(255,255,255,0.05)] rounded-[14px] transition-all active:scale-[0.98] border border-transparent hover:border-[rgba(255,255,255,0.1)]">
                    <i class="fas fa-cog text-[#3B82F6]"></i> Configure App
                </button>
            </div>
        </aside>

        <main class="flex-1 flex flex-col h-full w-full relative bg-transparent">
            
            <header class="absolute top-0 w-full z-30 flex items-center justify-between pt-12 pb-4 px-4 glass-heavy">
                <div class="flex items-center gap-4">
                    <button id="open-sidebar-btn" class="w-10 h-10 flex items-center justify-center text-[#3B82F6] bg-[rgba(255,255,255,0.05)] border border-[rgba(255,255,255,0.05)] rounded-full hover:bg-[rgba(255,255,255,0.1)] active:scale-90 transition-all shadow-sm">
                        <i class="fas fa-bars text-lg"></i>
                    </button>
                    <div class="flex items-center gap-3">
                        <h1 id="current-chat-title" class="text-[17px] font-semibold tracking-tight truncate max-w-[180px] drop-shadow-md">New Chat</h1>
                    </div>
                </div>
                <button id="export-btn" class="w-10 h-10 flex items-center justify-center text-[#A1A1AA] hover:text-white bg-[rgba(255,255,255,0.05)] border border-[rgba(255,255,255,0.05)] rounded-full transition-all hover:bg-[rgba(255,255,255,0.1)] active:scale-90" title="Export to Text">
                    <i class="fas fa-download text-[15px]"></i>
                </button>
            </header>

            <div id="chat-container" class="flex-1 overflow-y-auto pt-36 pb-40 px-4 md:px-12 lg:px-48 scroll-smooth relative z-10">
                <div id="messages-wrapper" class="flex flex-col gap-6 w-full max-w-3xl mx-auto pb-4">
                    
                    <div id="welcome-screen" class="flex flex-col items-center justify-center h-full text-center mt-24 animate-spring-up">
                        <div class="maxxi-avatar w-24 h-24 rounded-[24px] mb-6 shadow-[0_0_40px_rgba(37,99,235,0.5)] border border-[rgba(255,255,255,0.1)]">
                            <div class="maxxi-eyes"><div class="maxxi-eye" style="width:10px;height:10px;"></div><div class="maxxi-eye" style="width:10px;height:10px;"></div></div>
                            <div class="maxxi-smile" style="width:18px; margin-top:6px; border-width:3px;"></div>
                        </div>
                        <h2 class="text-[26px] font-bold tracking-tight mb-2 text-transparent bg-clip-text bg-gradient-to-r from-white to-[#A1A1AA]">Hello! I'm MAXXI AI.</h2>
                        <p class="text-[#A1A1AA] text-[15px] max-w-md mb-10 leading-relaxed">How can I assist you today? I'm ready to answer questions, brainstorm, or write code for you! 😊</p>
                        
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 w-full max-w-xl px-2">
                            <button onclick="window.sendQuickPrompt('Write a beautiful poem about stars and the universe.')" class="glass-card text-left p-4 rounded-[20px] active:scale-[0.98]">
                                <div class="font-medium text-[15px] text-white mb-1"><i class="fas fa-feather text-[#3B82F6] mr-2"></i>Write a poem</div>
                                <div class="text-[13px] text-[#A1A1AA] truncate">About the stars and universe</div>
                            </button>
                            <button onclick="window.sendQuickPrompt('Explain Quantum Mechanics simply.')" class="glass-card text-left p-4 rounded-[20px] active:scale-[0.98]">
                                <div class="font-medium text-[15px] text-white mb-1"><i class="fas fa-lightbulb text-purple-400 mr-2"></i>Explain simply</div>
                                <div class="text-[13px] text-[#A1A1AA] truncate">Quantum Mechanics made easy</div>
                            </button>
                        </div>
                    </div>

                </div>
            </div>

            <button id="scroll-fab" class="absolute bottom-[130px] right-6 w-11 h-11 bg-[rgba(30,30,35,0.8)] backdrop-blur-xl border border-[rgba(255,255,255,0.1)] rounded-full flex items-center justify-center text-white shadow-[0_8px_30px_rgba(0,0,0,0.6)] z-20 opacity-0 translate-y-4 pointer-events-none transition-all duration-300 hover:bg-[rgba(50,50,55,0.9)] active:scale-90">
                <i class="fas fa-arrow-down text-sm"></i>
            </button>

            <div class="absolute bottom-0 w-full bg-gradient-to-t from-[#030305] via-[#030305] to-transparent pt-12 pb-6 md:pb-8 px-4 md:px-12 lg:px-48 z-30">
                <div class="max-w-3xl mx-auto relative">
                    
                    <div class="glass-input rounded-[32px] flex flex-col overflow-hidden transition-all duration-300 focus-within:border-[#3B82F6] focus-within:shadow-[0_0_30px_rgba(37,99,235,0.2)]">
                        <input type="file" id="image-upload" accept="image/*" class="hidden">

                        <div id="image-preview-wrapper" class="max-h-0 opacity-0 overflow-hidden transition-all duration-300 px-4">
                            <div class="relative inline-block mt-4">
                                <img id="image-preview" src="" class="h-16 w-16 object-cover rounded-[14px] border border-[rgba(255,255,255,0.1)] shadow-md">
                                <button id="remove-image-btn" class="absolute -top-2 -right-2 bg-red-500 text-white rounded-full w-6 h-6 flex items-center justify-center text-xs shadow-[0_0_10px_rgba(239,68,68,0.5)] hover:scale-110 transition-transform">
                                    <i class="fas fa-times"></i>
                                </button>
                            </div>
                        </div>

                        <div class="flex items-end px-2 py-2">
                            <button id="upload-btn" class="p-3 mb-1 text-[#A1A1AA] hover:text-[#3B82F6] transition-colors rounded-full flex-shrink-0 bg-transparent hover:bg-[rgba(255,255,255,0.05)] active:scale-90" title="Attach Image">
                                <i class="fas fa-plus text-[20px]"></i>
                            </button>
                            
                            <textarea id="chat-input" rows="1" class="w-full max-h-32 bg-transparent text-white px-2 py-3.5 resize-none outline-none text-[16px] placeholder-[#71717A] leading-relaxed" placeholder="Message MAXXI..."></textarea>
                            
                            <button id="send-btn" disabled class="p-2.5 mb-1.5 mr-1 bg-[rgba(255,255,255,0.05)] text-[#52525B] rounded-full transition-all duration-300 flex items-center justify-center h-10 w-10 flex-shrink-0 disabled:opacity-70 disabled:bg-[rgba(255,255,255,0.03)] active:scale-90">
                                <i class="fas fa-arrow-up text-[16px]"></i>
                            </button>
                        </div>
                    </div>
                    
                    <div class="text-center text-[11px] text-[#71717A] mt-3 tracking-wide drop-shadow-md">
                        MAXXI AI can make mistakes. Verify important information.
                    </div>
                </div>
            </div>
        </main>
    </div>

    <div id="admin-modal" class="fixed inset-0 z-[200] hidden flex items-center justify-center bg-black/80 backdrop-blur-xl px-4 transition-opacity duration-300 opacity-0">
        <div id="admin-content" class="bg-[#121214] border border-[rgba(255,255,255,0.1)] rounded-[32px] w-full max-w-sm overflow-hidden shadow-[0_20px_60px_rgba(0,0,0,0.8)] transform scale-95 transition-transform duration-300">
            <div class="text-center pt-8 pb-4 px-6 border-b border-[rgba(255,255,255,0.05)]">
                <div class="w-14 h-14 bg-gradient-to-br from-[#1E3A8A] to-[#3B82F6] rounded-[16px] flex items-center justify-center mx-auto mb-4 shadow-[0_0_20px_rgba(37,99,235,0.4)] border border-white/10">
                    <i class="fas fa-shield-alt text-white text-2xl drop-shadow-md"></i>
                </div>
                <h2 class="text-[20px] font-semibold tracking-tight">System Config</h2>
                <p class="text-[13px] text-[#A1A1AA] mt-1">Configure API connections.</p>
            </div>
            
            <div class="p-6 space-y-4 max-h-[60vh] overflow-y-auto bg-[rgba(0,0,0,0.2)]">
                <div class="space-y-1.5">
                    <label class="block text-[12px] font-semibold text-[#A1A1AA] uppercase tracking-wider pl-1">OpenRouter API Key <span class="text-red-500">*</span></label>
                    <div class="relative">
                        <input type="password" id="admin-api-key" class="w-full bg-[#050505] border border-[rgba(255,255,255,0.1)] rounded-[14px] px-4 py-3.5 outline-none focus:border-[#3B82F6] transition-colors text-[14px] shadow-inner" placeholder="sk-or-v1-...">
                        <button type="button" id="toggle-visibility" class="absolute right-4 top-1/2 -translate-y-1/2 text-[#A1A1AA] hover:text-white transition-colors">
                            <i class="fas fa-eye"></i>
                        </button>
                    </div>
                </div>
                <div class="space-y-1.5">
                    <label class="block text-[12px] font-semibold text-[#A1A1AA] uppercase tracking-wider pl-1">Model ID</label>
                    <input type="text" id="admin-model" class="w-full bg-[#050505] border border-[rgba(255,255,255,0.1)] rounded-[14px] px-4 py-3.5 outline-none focus:border-[#3B82F6] transition-colors text-[14px] shadow-inner" placeholder="google/gemini-1.5-flash">
                </div>
                <div class="space-y-1.5">
                    <label class="block text-[12px] font-semibold text-[#A1A1AA] uppercase tracking-wider pl-1">System Prompt</label>
                    <textarea id="admin-prompt" rows="3" class="w-full bg-[#050505] border border-[rgba(255,255,255,0.1)] rounded-[14px] px-4 py-3.5 outline-none focus:border-[#3B82F6] transition-colors resize-none text-[14px] leading-relaxed shadow-inner" placeholder="You are MAXXI AI..."></textarea>
                </div>
                
                <div class="pt-4 mt-2">
                    <button id="clear-data-btn" class="w-full py-3.5 bg-transparent border border-red-500/30 text-red-400 rounded-[14px] text-[14px] font-medium hover:bg-red-500/10 transition-colors active:scale-[0.98]">
                        <i class="fas fa-trash-alt mr-2"></i> Wipe All Data
                    </button>
                </div>
            </div>

            <div class="flex border-t border-[rgba(255,255,255,0.05)] bg-[#121214]">
                <button id="close-admin-btn" class="flex-1 py-4.5 text-[16px] text-[#A1A1AA] font-normal border-r border-[rgba(255,255,255,0.05)] hover:bg-white/5 transition-colors active:bg-white/10">Cancel</button>
                <button id="save-admin-btn" class="flex-1 py-4.5 text-[16px] text-[#3B82F6] font-semibold hover:bg-white/5 transition-colors active:bg-white/10">Save Settings</button>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Setup syntax highlighting
            marked.setOptions({
                highlight: function(code, lang) {
                    if (lang && hljs.getLanguage(lang)) { try { return hljs.highlight(code, { language: lang }).value; } catch (__) {} }
                    return hljs.highlightAuto(code).value;
                }, breaks: true
            });

            // Storage Constants
            const CHAT_KEY = 'maxxi_chats_v3';
            const ADMIN_KEY = 'maxxi_admin_config_v3';

            // Universal fetch config function
            function getAdminConfig() {
                try {
                    const conf = JSON.parse(localStorage.getItem(ADMIN_KEY) || '{}');
                    return {
                        apiKey: conf.apiKey || '',
                        model: conf.model || 'google/gemini-1.5-flash',
                        systemPrompt: conf.systemPrompt || 'You are MAXXI AI (nickname: Macmilan), a highly intelligent and friendly assistant. Keep answers clear, accurate, and beautifully formatted.'
                    };
                } catch(e) {
                    return { apiKey: '', model: 'google/gemini-1.5-flash', systemPrompt: 'You are MAXXI AI (nickname: Macmilan).' };
                }
            }

            let state = { chats: [], activeChatId: null, isGenerating: false, currentImageBase64: null };
            let abortController = null;

            const DOM = {
                loading: document.getElementById('loading'), app: document.getElementById('app'),
                sidebar: document.getElementById('sidebar'), sidebarOverlay: document.getElementById('sidebar-overlay'),
                openSidebarBtn: document.getElementById('open-sidebar-btn'), closeSidebarBtn: document.getElementById('close-sidebar-btn'),
                newChatBtn: document.getElementById('new-chat-btn'), chatHistoryList: document.getElementById('chat-history-list'),
                currentChatTitle: document.getElementById('current-chat-title'), chatContainer: document.getElementById('chat-container'), 
                messagesWrapper: document.getElementById('messages-wrapper'), welcomeScreen: document.getElementById('welcome-screen'), 
                chatInput: document.getElementById('chat-input'), sendBtn: document.getElementById('send-btn'), 
                uploadBtn: document.getElementById('upload-btn'), imageUploadInput: document.getElementById('image-upload'), 
                imagePreviewWrapper: document.getElementById('image-preview-wrapper'), imagePreview: document.getElementById('image-preview'), 
                removeImageBtn: document.getElementById('remove-image-btn'), exportBtn: document.getElementById('export-btn'),
                searchInput: document.getElementById('chat-search'), scrollFab: document.getElementById('scroll-fab'),
                
                // Admin Nodes
                adminModal: document.getElementById('admin-modal'), adminContent: document.getElementById('admin-content'),
                openAdminBtn: document.getElementById('open-admin-btn'), closeAdminBtn: document.getElementById('close-admin-btn'),
                saveAdminBtn: document.getElementById('save-admin-btn'), adminApiKey: document.getElementById('admin-api-key'),
                adminModel: document.getElementById('admin-model'), adminPrompt: document.getElementById('admin-prompt'),
                toggleVis: document.getElementById('toggle-visibility'), clearDataBtn: document.getElementById('clear-data-btn')
            };

            function init() {
                loadState(); renderChatList();
                if (state.chats.length === 0) createNewChat(false);
                else { if (!state.activeChatId) state.activeChatId = state.chats[0].id; renderActiveChat(); }
                setupEventListeners(); updateSendButtonState();
                setTimeout(() => { DOM.loading.classList.add('opacity-0'); setTimeout(() => { DOM.loading.style.display = 'none'; DOM.app.classList.remove('hidden'); requestAnimationFrame(() => DOM.app.classList.remove('opacity-0')); }, 500); }, 800);
            }

            function loadState() {
                try { const savedChats = localStorage.getItem(CHAT_KEY); if (savedChats) { state.chats = JSON.parse(savedChats); if (!Array.isArray(state.chats)) state.chats = []; } } catch (e) { state.chats = []; }
            }

            function saveState() {
                try { localStorage.setItem(CHAT_KEY, JSON.stringify(state.chats)); } catch (e) { console.error("Storage Error"); }
            }

            function toggleSidebar(show) {
                try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                if (show) { DOM.sidebarOverlay.classList.remove('hidden'); void DOM.sidebarOverlay.offsetWidth; DOM.sidebarOverlay.classList.remove('opacity-0'); DOM.sidebar.classList.remove('-translate-x-full'); } 
                else { DOM.sidebarOverlay.classList.add('opacity-0'); DOM.sidebar.classList.add('-translate-x-full'); setTimeout(() => DOM.sidebarOverlay.classList.add('hidden'), 300); }
            }

            function generateId() { return Date.now().toString(36) + Math.random().toString(36).substr(2); }

            // FIX: Bulletproof New Chat Function
            function createNewChat(render = true) {
                try {
                    try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                    const newChat = { id: generateId(), title: 'New Chat', messages: [], createdAt: Date.now() };
                    state.chats.unshift(newChat); 
                    state.activeChatId = newChat.id; 
                    saveState(); 
                    if(DOM.searchInput) DOM.searchInput.value = '';
                    if (render) { 
                        renderChatList(); 
                        renderActiveChat(); 
                        if (window.innerWidth < 768) toggleSidebar(false); 
                    }
                } catch(err) {
                    console.error("Failed to create new chat:", err);
                }
            }

            function deleteChat(id, e) {
                e.stopPropagation(); try{ if(navigator.vibrate) navigator.vibrate(15); }catch(e){}
                if(!confirm("Delete this chat?")) return;
                state.chats = state.chats.filter(c => c.id !== id);
                if (state.activeChatId === id) state.activeChatId = state.chats.length > 0 ? state.chats[0].id : null;
                if (state.chats.length === 0) createNewChat(false);
                saveState(); renderChatList(); renderActiveChat();
            }

            function selectChat(id) {
                if(state.isGenerating) return; try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                state.activeChatId = id; renderChatList(); renderActiveChat();
                if (window.innerWidth < 768) toggleSidebar(false);
            }

            DOM.newChatBtn.addEventListener('click', () => createNewChat(true));

            DOM.searchInput.addEventListener('input', (e) => renderChatList(e.target.value.toLowerCase()));

            function renderChatList(filterTerm = '') {
                DOM.chatHistoryList.innerHTML = '';
                state.chats.forEach(chat => {
                    if (filterTerm && !chat.title.toLowerCase().includes(filterTerm)) return;
                    const isActive = chat.id === state.activeChatId;
                    const div = document.createElement('div');
                    div.className = `group flex items-center justify-between px-4 py-3.5 rounded-xl cursor-pointer mb-1 transition-all ${isActive ? 'bg-[rgba(255,255,255,0.08)] text-white border border-[rgba(255,255,255,0.05)] shadow-sm' : 'text-[#A1A1AA] hover:bg-[rgba(255,255,255,0.03)] border border-transparent'}`;
                    div.innerHTML = `<div class="flex items-center gap-3 overflow-hidden flex-1" onclick="window.selectChatHandler('${chat.id}')"><i class="fas fa-comment-alt text-[12px] opacity-50"></i><span class="truncate text-[14px] font-medium tracking-wide">${escapeHTML(chat.title)}</span></div><button onclick="window.deleteChatHandler('${chat.id}', event)" class="opacity-0 md:group-hover:opacity-100 p-1.5 text-red-500 hover:text-red-400 hover:scale-110 transition-all"><i class="fas fa-trash-alt text-[13px]"></i></button>`;
                    DOM.chatHistoryList.appendChild(div);
                });
            }

            window.selectChatHandler = selectChat; window.deleteChatHandler = deleteChat;
            window.sendQuickPrompt = function(txt) { DOM.chatInput.value = txt; DOM.chatInput.dispatchEvent(new Event('input')); sendMessage(); };

            // Admin Logic
            DOM.openAdminBtn.addEventListener('click', () => {
                const conf = getAdminConfig();
                DOM.adminApiKey.value = conf.apiKey; DOM.adminModel.value = conf.model; DOM.adminPrompt.value = conf.systemPrompt;
                DOM.adminModal.classList.remove('hidden'); void DOM.adminModal.offsetWidth;
                DOM.adminModal.classList.remove('opacity-0'); DOM.adminContent.classList.remove('scale-95');
                if (window.innerWidth < 768) toggleSidebar(false);
            });
            DOM.closeAdminBtn.addEventListener('click', () => {
                DOM.adminModal.classList.add('opacity-0'); DOM.adminContent.classList.add('scale-95');
                setTimeout(() => DOM.adminModal.classList.add('hidden'), 300);
            });
            DOM.saveAdminBtn.addEventListener('click', () => {
                const config = { apiKey: DOM.adminApiKey.value.trim(), model: DOM.adminModel.value.trim(), systemPrompt: DOM.adminPrompt.value.trim() };
                localStorage.setItem(ADMIN_KEY, JSON.stringify(config));
                DOM.closeAdminBtn.click();
            });
            DOM.toggleVis.addEventListener('click', () => {
                if (DOM.adminApiKey.type === 'password') { DOM.adminApiKey.type = 'text'; DOM.toggleVis.innerHTML = '<i class="fas fa-eye-slash"></i>'; } 
                else { DOM.adminApiKey.type = 'password'; DOM.toggleVis.innerHTML = '<i class="fas fa-eye"></i>'; }
            });
            DOM.clearDataBtn.addEventListener('click', () => {
                if(confirm("DANGER: Wipe all chats and settings?")) { localStorage.clear(); location.reload(); }
            });

            // Export Chat
            DOM.exportBtn.addEventListener('click', () => {
                const chat = state.chats.find(c => c.id === state.activeChatId);
                if(!chat || chat.messages.length === 0) return alert("Chat is empty.");
                let txt = `Chat: ${chat.title}\n\n`;
                chat.messages.forEach(m => { txt += `[${m.role === 'user' ? 'You' : 'MAXXI AI'}]\n${m.content}\n\n`; });
                const a = document.createElement('a'); a.href = URL.createObjectURL(new Blob([txt], { type: 'text/plain' })); a.download = `${chat.title}.txt`; a.click();
            });

            // Image Handler
            DOM.uploadBtn.addEventListener('click', () => DOM.imageUploadInput.click());
            DOM.imageUploadInput.addEventListener('change', (e) => {
                const file = e.target.files[0]; if (!file) return;
                const reader = new FileReader();
                reader.onload = function(event) {
                    const img = new Image();
                    img.onload = function() {
                        let w = img.width; let h = img.height;
                        if (w > h && w > 800) { h *= 800 / w; w = 800; } else if (h > 800) { w *= 800 / h; h = 800; }
                        const canvas = document.createElement('canvas'); canvas.width = w; canvas.height = h;
                        canvas.getContext('2d').drawImage(img, 0, 0, w, h);
                        state.currentImageBase64 = canvas.toDataURL('image/jpeg', 0.7);
                        DOM.imagePreview.src = state.currentImageBase64; 
                        DOM.imagePreviewWrapper.style.maxHeight = '150px'; DOM.imagePreviewWrapper.style.opacity = '1'; DOM.imagePreviewWrapper.style.paddingBottom = '12px'; DOM.imagePreviewWrapper.style.marginTop = '8px';
                        updateSendButtonState();
                    };
                    img.src = event.target.result;
                };
                reader.readAsDataURL(file); DOM.imageUploadInput.value = '';
            });
            DOM.removeImageBtn.addEventListener('click', () => { 
                state.currentImageBase64 = null; DOM.imagePreview.src = ''; 
                DOM.imagePreviewWrapper.style.maxHeight = '0'; DOM.imagePreviewWrapper.style.opacity = '0'; DOM.imagePreviewWrapper.style.paddingBottom = '0'; DOM.imagePreviewWrapper.style.marginTop = '0';
                updateSendButtonState(); 
            });

            // FIX: BULLETPROOF COPY ENGINE
            window.copyText = function(btn, base64Text) {
                try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                let textToCopy = ""; try { textToCopy = decodeURIComponent(escape(atob(base64Text))); } catch(e) { return; }

                const successUI = () => {
                    const orig = btn.innerHTML; 
                    btn.innerHTML = '<i class="fas fa-check text-green-500"></i> <span class="text-green-500">Copied</span>'; 
                    setTimeout(() => btn.innerHTML = orig, 2000);
                };

                const fallbackCopy = () => {
                    const textArea = document.createElement("textarea"); textArea.value = textToCopy; textArea.style.position = "fixed"; textArea.style.opacity = "0"; 
                    document.body.appendChild(textArea); textArea.focus(); textArea.select();
                    try { if(document.execCommand('copy')) successUI(); else window.prompt("Copy text below:", textToCopy); } catch (err) { window.prompt("Copy text below:", textToCopy); }
                    document.body.removeChild(textArea);
                };

                if (navigator.clipboard && window.isSecureContext) navigator.clipboard.writeText(textToCopy).then(successUI).catch(fallbackCopy); else fallbackCopy(); 
            };

            window.regenerateResponse = function(btn) {
                if (state.isGenerating) return; try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                const chat = state.chats.find(c => c.id === state.activeChatId);
                if (!chat || chat.messages.length < 2) return;
                const icon = btn.querySelector('i'); icon.classList.add('animate-spin');
                if (chat.messages[chat.messages.length - 1].role === 'assistant') chat.messages.pop();
                saveState(); renderActiveChat(); triggerAPI();
            };

            function renderActiveChat() {
                const chat = state.chats.find(c => c.id === state.activeChatId); if (!chat) return;
                DOM.currentChatTitle.textContent = chat.title; DOM.messagesWrapper.innerHTML = '';
                if (chat.messages.length === 0) DOM.welcomeScreen.style.display = 'flex';
                else { DOM.welcomeScreen.style.display = 'none'; chat.messages.forEach(msg => appendMessageToUI(msg.role, msg.content, msg.image, false, false)); }
                DOM.chatContainer.scrollTop = DOM.chatContainer.scrollHeight;
            }

            function escapeHTML(str) { return str ? str.replace(/[&<>'"]/g, tag => ({'&': '&amp;','<': '&lt;','>': '&gt;',"'": '&#39;','"': '&quot;'}[tag] || tag)) : ''; }

            // Apply syntax wrapper to code blocks
            function enhanceCodeBlocks(container) {
                const pres = container.querySelectorAll('pre');
                pres.forEach(pre => {
                    if (pre.parentNode.classList.contains('code-block-wrapper')) return; 
                    const wrapper = document.createElement('div'); wrapper.className = 'code-block-wrapper'; pre.parentNode.insertBefore(wrapper, pre);
                    let lang = 'Code'; const codeNode = pre.querySelector('code');
                    if (codeNode && codeNode.className) { const match = codeNode.className.match(/language-(\w+)/); if (match) lang = match[1]; }
                    const header = document.createElement('div'); header.className = 'code-header';
                    header.innerHTML = `
                        <div class="flex items-center gap-2"><div class="flex gap-1.5 mr-2"><div class="w-2.5 h-2.5 rounded-full bg-[#FF5F56]"></div><div class="w-2.5 h-2.5 rounded-full bg-[#FFBD2E]"></div><div class="w-2.5 h-2.5 rounded-full bg-[#27C93F]"></div></div><span class="opacity-70">${lang}</span></div>
                        <button onclick="window.copyText(this, '${btoa(unescape(encodeURIComponent(pre.innerText)))}')" class="hover:text-white transition-colors flex items-center gap-1.5 active:scale-95 bg-[rgba(255,255,255,0.05)] px-2.5 py-1 rounded-md border border-[rgba(255,255,255,0.05)]"><i class="far fa-copy"></i> Copy</button>`;
                    wrapper.appendChild(header); wrapper.appendChild(pre);
                });
            }

            function appendMessageToUI(role, content, imageBase64, isStreaming = false, animate = true) {
                const msgDiv = document.createElement('div');
                msgDiv.className = `flex w-full ${role === 'user' ? 'justify-end' : 'justify-start'} ${animate ? 'animate-message-pop' : ''}`;
                const innerDiv = document.createElement('div');
                
                if (role === 'user') {
                    innerDiv.className = 'max-w-[85%] md:max-w-[75%] bg-[#27272A] text-white px-5 py-3.5 rounded-[24px] rounded-br-[6px] flex flex-col gap-2 shadow-[0_2px_10px_rgba(0,0,0,0.2)] border border-[rgba(255,255,255,0.05)]';
                    let htmlContent = '';
                    if (imageBase64) htmlContent += `<img src="${imageBase64}" class="w-full max-w-sm rounded-[14px] object-cover mb-2 border border-white/10">`;
                    if (content) htmlContent += `<div class="whitespace-pre-wrap break-words text-[16px]">${escapeHTML(content)}</div>`;
                    innerDiv.innerHTML = htmlContent;
                } else {
                    innerDiv.className = 'w-full max-w-[100%] flex gap-4 text-white py-1 relative group';
                    const avatar = document.createElement('div');
                    avatar.className = 'maxxi-avatar w-9 h-9 rounded-[12px] justify-center flex-shrink-0 mt-1';
                    avatar.innerHTML = '<div class="maxxi-eyes"><div class="maxxi-eye" style="width:4px;height:4px;"></div><div class="maxxi-eye" style="width:4px;height:4px;"></div></div><div class="maxxi-smile" style="width:6px; margin-top:1px;"></div>';
                    
                    const contentContainer = document.createElement('div'); contentContainer.className = 'flex-1 min-w-0 flex flex-col pt-1.5';
                    const mdContainer = document.createElement('div'); mdContainer.className = 'markdown-body text-[16px] text-[#E5E7EB]';
                    
                    if (isStreaming) { 
                        mdContainer.innerHTML = '<div class="typing-indicator"><span class="typing-dot"></span><span class="typing-dot"></span><span class="typing-dot"></span></div>'; 
                    } else if (content.startsWith("Error:")) { 
                        // Exact Red Error UI from screenshot
                        mdContainer.innerHTML = `<div class="bg-[#3A1C1C] text-[#FF6B6B] px-5 py-4 rounded-[22px] rounded-bl-[6px] border border-[#5A2A2A] font-medium leading-relaxed shadow-sm w-fit max-w-[95%]">${content}</div>`; 
                    } else { 
                        mdContainer.innerHTML = marked.parse(content || ''); enhanceCodeBlocks(mdContainer);
                    }

                    contentContainer.appendChild(mdContainer);

                    // Copy & Regenerate Ghost Buttons
                    if (!isStreaming && !content.startsWith("Error:")) {
                        const safeBase64 = btoa(unescape(encodeURIComponent(content || '')));
                        const actionBar = document.createElement('div');
                        actionBar.className = 'mt-3 flex flex-wrap gap-2 transition-opacity'; 
                        actionBar.innerHTML = `
                            <button onclick="window.copyText(this, '${safeBase64}')" class="flex items-center gap-1.5 px-3 py-1.5 bg-[rgba(255,255,255,0.03)] hover:bg-[rgba(255,255,255,0.08)] rounded-[12px] transition-colors text-[#A1A1AA] hover:text-white text-[13px] font-medium active:scale-95 border border-[rgba(255,255,255,0.05)]">
                                <i class="far fa-copy"></i> <span>Copy</span>
                            </button>
                            <button onclick="window.regenerateResponse(this)" class="flex items-center gap-1.5 px-3 py-1.5 bg-[rgba(255,255,255,0.03)] hover:bg-[rgba(255,255,255,0.08)] rounded-[12px] transition-colors text-[#A1A1AA] hover:text-white text-[13px] font-medium active:scale-95 border border-[rgba(255,255,255,0.05)]">
                                <i class="fas fa-redo text-[11px]"></i> <span>Regenerate</span>
                            </button>
                        `;
                        contentContainer.appendChild(actionBar);
                    }

                    innerDiv.appendChild(avatar); innerDiv.appendChild(contentContainer);
                }

                msgDiv.appendChild(innerDiv); DOM.messagesWrapper.appendChild(msgDiv);
                if (animate) smoothScrollToBottom(); return msgDiv;
            }

            // FIX: SCROLL TO BOTTOM LOGIC
            function smoothScrollToBottom() { 
                if(!DOM.chatContainer) return;
                DOM.chatContainer.scrollTo({ top: DOM.chatContainer.scrollHeight, behavior: 'smooth' }); 
            }

            DOM.chatContainer.addEventListener('scroll', () => {
                const isNearBottom = DOM.chatContainer.scrollHeight - DOM.chatContainer.scrollTop - DOM.chatContainer.clientHeight < 250;
                if (!isNearBottom && DOM.chatContainer.scrollHeight > DOM.chatContainer.clientHeight * 1.5) {
                    DOM.scrollFab.classList.remove('opacity-0', 'pointer-events-none', 'translate-y-4');
                } else {
                    DOM.scrollFab.classList.add('opacity-0', 'pointer-events-none', 'translate-y-4');
                }
            });
            DOM.scrollFab.addEventListener('click', () => {
                try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                smoothScrollToBottom();
            });

            async function sendMessage() {
                const text = DOM.chatInput.value.trim(); const imageToSend = state.currentImageBase64;
                if ((!text && !imageToSend) || state.isGenerating) return;

                // Load Settings Live from Admin Config
                const conf = getAdminConfig();

                if (!conf.apiKey) {
                    const chat = state.chats.find(c => c.id === state.activeChatId);
                    if (chat) {
                        chat.messages.push({ role: 'user', content: text });
                        chat.messages.push({ role: 'assistant', content: "Error: No API Key found. Admin panel configuration required." });
                        saveState(); renderActiveChat();
                    }
                    return;
                }

                try{ if(navigator.vibrate) navigator.vibrate(10); }catch(e){}
                const chat = state.chats.find(c => c.id === state.activeChatId); if (!chat) return;
                DOM.welcomeScreen.style.display = 'none'; DOM.chatInput.value = ''; DOM.chatInput.style.height = 'auto'; 
                state.currentImageBase64 = null; DOM.imagePreviewWrapper.style.maxHeight = '0'; DOM.imagePreviewWrapper.style.opacity = '0'; DOM.imagePreviewWrapper.style.paddingBottom = '0'; DOM.imagePreviewWrapper.style.marginTop = '0';
                
                chat.messages.push({ role: 'user', content: text, image: imageToSend });
                appendMessageToUI('user', text, imageToSend, false, true); saveState();
                if (chat.messages.length === 1) { chat.title = text ? (text.length > 20 ? text.substring(0, 20) + '...' : text) : 'Image Chat'; DOM.currentChatTitle.textContent = chat.title; renderChatList(); }
                triggerAPI(conf);
            }

            // FIX: PROVIDER ERROR HANDLING & PAYLOAD
            async function triggerAPI(conf) {
                const chat = state.chats.find(c => c.id === state.activeChatId);
                state.isGenerating = true; updateSendButtonState();
                const streamNode = appendMessageToUI('assistant', '', null, true, true); const mdContainer = streamNode.querySelector('.markdown-body'); let aiFullResponse = "";
                
                const apiMessages = [];
                if(conf.systemPrompt) apiMessages.push({ role: 'system', content: conf.systemPrompt });
                chat.messages.forEach(m => {
                    if (m.role === 'user' && m.image) { 
                        apiMessages.push({ role: 'user', content: [{ type: "text", text: m.content || "Describe this image." }, { type: "image_url", image_url: { url: m.image } }] }); 
                    } else if (m.role !== 'system') { 
                        // Text only models will crash if you send them a blank array, strictly string
                        apiMessages.push({ role: m.role, content: m.content }); 
                    }
                });

                abortController = new AbortController();
                try {
                    const response = await fetch('https://openrouter.ai/api/v1/chat/completions', {
                        method: 'POST', headers: { 'Content-Type': 'application/json', 'Authorization': `Bearer ${conf.apiKey}` },
                        body: JSON.stringify({ model: conf.model, messages: apiMessages, stream: true }), signal: abortController.signal
                    });
                    
                    if (!response.ok) {
                        let errTxt = `Error ${response.status}: Provider returned error`;
                        try {
                            const errData = await response.json();
                            errTxt = `Error: ${errData.error?.message || errData.error || 'Provider returned error'}`;
                        } catch(e){}
                        throw new Error(errTxt);
                    }
                    if (!response.body) throw new Error("Stream not supported.");

                    const reader = response.body.getReader(); const decoder = new TextDecoder(); let buffer = ''; let isFirstChunk = true;
                    while (true) {
                        const { done, value } = await reader.read(); if (done) break;
                        buffer += decoder.decode(value, { stream: true }); const lines = buffer.split('\n'); buffer = lines.pop(); 
                        for (const line of lines) {
                            if (line.trim() === 'data: [DONE]') continue;
                            if (line.startsWith('data: ')) {
                                try {
                                    const data = JSON.parse(line.slice(6)); const content = data.choices[0]?.delta?.content;
                                    if (content) {
                                        if (isFirstChunk) { mdContainer.innerHTML = ''; isFirstChunk = false; }
                                        aiFullResponse += content; mdContainer.innerHTML = marked.parse(aiFullResponse);
                                        // Auto-scroll ONLY if user is already at the bottom
                                        if(DOM.chatContainer.scrollHeight - DOM.chatContainer.scrollTop - DOM.chatContainer.clientHeight < 150) smoothScrollToBottom();
                                    }
                                } catch (e) {}
                            }
                        }
                    }
                } catch (error) {
                    if (error.name === 'AbortError') { aiFullResponse += "\n\n*[Stopped]*"; } 
                    else { 
                        let errMsg = error.message;
                        // Provide useful hints for OpenRouter
                        if(errMsg.toLowerCase().includes("image") || errMsg.toLowerCase().includes("vision")) {
                            errMsg += "<br><br><span class='text-sm opacity-80'>Tip: Make sure the Model Name in the Admin settings supports Vision (e.g. <code>google/gemini-1.5-flash</code>)</span>";
                        } else if (errMsg.includes("401") || errMsg.includes("authentication")) {
                            errMsg += "<br><br><span class='text-sm opacity-80'>Tip: Check if your API Key in Admin Settings is correct.</span>";
                        }
                        aiFullResponse = errMsg.startsWith("Error:") ? errMsg : `Error: ${errMsg}`; 
                    }
                } finally {
                    if (aiFullResponse !== "") {
                        chat.messages.push({ role: 'assistant', content: aiFullResponse });
                        if (streamNode && streamNode.parentNode) streamNode.remove();
                        appendMessageToUI('assistant', aiFullResponse, null, false, false);
                    }
                    saveState(); state.isGenerating = false; abortController = null; updateSendButtonState(); smoothScrollToBottom();
                }
            }

            function updateSendButtonState() {
                if (state.isGenerating) {
                    DOM.sendBtn.removeAttribute('disabled'); DOM.sendBtn.innerHTML = '<i class="fas fa-stop text-[14px]"></i>';
                    DOM.sendBtn.classList.replace('bg-[rgba(255,255,255,0.05)]', 'bg-red-500/20'); DOM.sendBtn.classList.replace('text-[#52525B]', 'text-red-400');
                } else {
                    DOM.sendBtn.innerHTML = '<i class="fas fa-arrow-up text-[16px]"></i>';
                    const hasText = DOM.chatInput.value.trim().length > 0; const hasImage = !!state.currentImageBase64;
                    if (hasText || hasImage) { DOM.sendBtn.removeAttribute('disabled'); DOM.sendBtn.classList.add('bg-[#2563EB]', 'text-white', 'shadow-[0_0_15px_rgba(37,99,235,0.4)]'); DOM.sendBtn.classList.remove('bg-[rgba(255,255,255,0.05)]', 'text-[#52525B]', 'bg-red-500/20', 'text-red-400'); } 
                    else { DOM.sendBtn.setAttribute('disabled', 'true'); DOM.sendBtn.classList.add('bg-[rgba(255,255,255,0.05)]', 'text-[#52525B]'); DOM.sendBtn.classList.remove('bg-[#2563EB]', 'text-white', 'bg-red-500/20', 'text-red-400', 'shadow-[0_0_15px_rgba(37,99,235,0.4)]'); }
                }
            }

            function setupEventListeners() {
                DOM.chatInput.addEventListener('input', function() { this.style.height = 'auto'; this.style.height = Math.min(this.scrollHeight, 120) + 'px'; updateSendButtonState(); });
                DOM.chatInput.addEventListener('keydown', (e) => { if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); if (!DOM.sendBtn.disabled) { if(state.isGenerating) abortController?.abort(); else sendMessage(); } } });
                DOM.sendBtn.addEventListener('click', () => { if (state.isGenerating && abortController) abortController.abort(); else sendMessage(); });
                DOM.openSidebarBtn.addEventListener('click', () => toggleSidebar(true));
                DOM.closeSidebarBtn.addEventListener('click', () => toggleSidebar(false));
                DOM.sidebarOverlay.addEventListener('click', () => toggleSidebar(false));
            }
            init();
        });
    </script>
</body>
</html>