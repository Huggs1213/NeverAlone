<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Never Alone - Women's Safety Network</title>
    
    <!-- PWA Web App Manifest -->
    <link rel="manifest" href='data:application/manifest+json,{"name":"Never Alone","short_name":"NeverAlone","start_url":".","display":"standalone","background_color":"#ffffff","theme_color":"#be123c"}'>
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="theme-color" content="#be123c">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Leaflet OpenStreetMap CDN -->
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

    <style>
        #map { height: calc(100vh - 220px); width: 100%; }
        .tab-content { display: none; }
        .tab-content.active { display: block; }
        body { -webkit-tap-highlight-color: transparent; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans pb-20 select-none">

    <!-- Top Navigation Header -->
    <header class="bg-rose-700 text-white p-4 sticky top-0 z-50 shadow-md flex justify-between items-center">
        <div class="flex items-center gap-2">
            <i class="fa-solid fa-shield-halved text-2xl"></i>
            <h1 class="font-bold text-xl tracking-wide">Never Alone</h1>
        </div>
        <button onclick="triggerQuickSOS()" class="bg-red-600 hover:bg-red-700 text-white font-black px-3 py-1 rounded-full text-xs uppercase tracking-wider animate-pulse border-2 border-white">
            <i class="fa-solid fa-bolt mr-1"></i> Quick SOS
        </button>
    </header>

    <!-- Main App Content Area -->
    <main class="max-w-md mx-auto">

        <!-- TAB 1: SOS EMERGENCY -->
        <section id="tab-sos" class="tab-content active p-4 space-y-4">
            <div class="bg-rose-50 border border-rose-200 rounded-2xl p-5 text-center space-y-4 shadow-sm">
                <div class="inline-block p-3 bg-rose-100 rounded-full">
                    <i class="fa-solid fa-triangle-exclamation text-3xl text-rose-600"></i>
                </div>
                <h2 class="text-2xl font-black text-rose-900">Emergency Response</h2>
                <p class="text-xs text-rose-700">Tap below to sound an audio siren, dispatch live GPS location to 3 contacts, or dial 911.</p>
                
                <button onclick="triggerFullSOS()" class="w-44 h-44 mx-auto bg-gradient-to-tr from-rose-600 to-red-500 rounded-full shadow-2xl flex flex-col items-center justify-center text-white border-8 border-rose-200 active:scale-95 transition-transform">
                    <i class="fa-solid fa-bell text-4xl mb-1"></i>
                    <span class="text-2xl font-black tracking-widest">SOS</span>
                </button>

                <div class="grid grid-cols-2 gap-2 pt-2">
                    <button onclick="toggleSiren()" id="sirenBtn" class="bg-slate-800 text-white p-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2">
                        <i class="fa-solid fa-volume-high text-rose-400"></i> <span id="sirenText">Loud Siren</span>
                    </button>
                    <a id="smsEmergencyLink" href="sms:?body=EMERGENCY!" class="bg-rose-600 text-white p-3 rounded-xl font-bold text-xs flex items-center justify-center gap-2 text-center shadow">
                        <i class="fa-solid fa-comment-sms"></i> Alert 3 Contacts
                    </a>
                </div>

                <a href="tel:911" class="block w-full bg-red-700 hover:bg-red-800 text-white py-3 rounded-xl font-bold text-xs text-center shadow animate-pulse">
                    <i class="fa-solid fa-phone-flip mr-1"></i> Call 911 Direct
                </a>
            </div>

            <!-- 3 Emergency Contacts Setup -->
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-slate-200 space-y-3">
                <h3 class="font-bold text-sm text-slate-700 flex items-center gap-2">
                    <i class="fa-solid fa-users-shield text-rose-600"></i> Save 3 Emergency Contacts
                </h3>
                <div class="space-y-2">
                    <input type="tel" id="contactPhone1" placeholder="Contact 1 Phone Number" class="w-full border border-slate-300 rounded-xl px-3 py-2 text-xs focus:outline-rose-600">
                    <input type="tel" id="contactPhone2" placeholder="Contact 2 Phone Number" class="w-full border border-slate-300 rounded-xl px-3 py-2 text-xs focus:outline-rose-600">
                    <input type="tel" id="contactPhone3" placeholder="Contact 3 Phone Number" class="w-full border border-slate-300 rounded-xl px-3 py-2 text-xs focus:outline-rose-600">
                </div>
                <button onclick="saveAllContacts()" class="w-full bg-slate-900 hover:bg-slate-800 text-white py-2 rounded-xl text-xs font-bold transition-colors">
                    Save Emergency Contacts
                </button>
                <p id="savedContactsStatus" class="text-xs text-emerald-600 font-medium"></p>
            </div>

            <!-- $4.99 Super Pass Banner -->
            <div class="bg-gradient-to-r from-rose-700 to-purple-900 p-4 rounded-2xl text-white shadow-md space-y-2">
                <div class="flex justify-between items-center">
                    <h3 class="font-bold text-sm"><i class="fa-solid fa-star text-amber-300 mr-1"></i> Never Alone Super Pass</h3>
                    <span class="bg-emerald-500 text-white text-[10px] uppercase font-black px-2 py-0.5 rounded-full">$4.99 ONE-TIME</span>
                </div>
                <p class="text-xs text-rose-100">Core safety stays free forever. Upgrade once to unlock custom Fake Caller IDs, custom emergency text wording, and unlimited SafeWalk check-ins.</p>
                <a href="YOUR_499_STRIPE_LINK" target="_blank" class="block text-center bg-white text-rose-800 font-bold py-2 rounded-xl text-xs shadow hover:bg-rose-50 transition-colors">
                    Unlock Super Features ($4.99 Lifetime)
                </a>
            </div>
        </section>

        <!-- TAB 2: INCIDENT & SAFE HAVEN MAP -->
        <section id="tab-map" class="tab-content relative">
            <!-- $9.99 Business Banner -->
            <div class="bg-slate-900 text-white p-3.5 rounded-2xl shadow-md space-y-1.5 m-3 border border-slate-800">
                <div class="flex justify-between items-center">
                    <h3 class="font-bold text-xs text-rose-400 flex items-center gap-1.5">
                        <i class="fa-solid fa-store"></i> Local Business Owner?
                    </h3>
                    <span class="bg-rose-600 text-white text-[10px] font-black px-2 py-0.5 rounded-full">$9.99 FLAT FEE</span>
                </div>
                <p class="text-[11px] text-slate-300">Get listed as a permanent green "Verified Safe Haven" marker on our map.</p>
                <a href="YOUR_999_STRIPE_LINK" target="_blank" class="block text-center bg-rose-600 hover:bg-rose-700 text-white font-bold py-1.5 rounded-xl text-xs shadow transition-colors">
                    Apply for Safe Haven Verification ($9.99)
                </a>
            </div>

            <div class="p-2 bg-white border-b border-slate-200 flex justify-between items-center px-4">
                <span class="text-xs font-bold text-slate-600"><i class="fa-solid fa-location-dot text-rose-600 mr-1"></i> Safety Map</span>
                <button onclick="openReportModal()" class="bg-rose-600 text-white text-xs font-bold px-3 py-1.5 rounded-lg shadow">
                    <i class="fa-solid fa-plus mr-1"></i> Add Pin
                </button>
            </div>
            <div id="map"></div>
        </section>

        <!-- TAB 3: WOMEN-ONLY RIDES -->
        <section id="tab-rides" class="tab-content p-4 space-y-4">
            <!-- SheSafe Driver Status Banner -->
            <div class="bg-slate-900 text-white p-4 rounded-2xl shadow border border-slate-800 space-y-2">
                <div class="flex justify-between items-center">
                    <h3 class="font-bold text-xs text-rose-400 flex items-center gap-1.5">
                        <i class="fa-solid fa-id-card"></i> SheSafe Driver Status
                    </h3>
                    <span id="driverStatusBadge" class="bg-amber-500/20 text-amber-300 text-[10px] font-bold px-2 py-0.5 rounded-full border border-amber-500/30">
                        Unverified
                    </span>
                </div>
                <p class="text-[11px] text-slate-300">To offer rides to women, drivers must verify their government photo ID.</p>
                <button onclick="startDriverVerification()" class="w-full bg-rose-600 hover:bg-rose-700 text-white font-bold py-2 rounded-xl text-xs transition-colors shadow">
                    Verify ID to Become a SheSafe Driver
                </button>
            </div>

            <div class="flex justify-between items-center">
                <h2 class="font-bold text-lg text-slate-800">Women's Ride Share</h2>
                <button onclick="openRideModal()" class="bg-rose-600 text-white text-xs font-bold px-3 py-2 rounded-xl shadow">
                    <i class="fa-solid fa-car mr-1"></i> Post Ride / Request
                </button>
            </div>
            <div id="ridesList" class="space-y-3">
                <!-- Dynamically populated -->
            </div>
        </section>

        <!-- TAB 4: ADVICE FORUM -->
        <section id="tab-forum" class="tab-content p-4 space-y-4">
            <div class="flex justify-between items-center">
                <h2 class="font-bold text-lg text-slate-800">Women's Advice Forum</h2>
                <button onclick="openForumModal()" class="bg-rose-600 text-white text-xs font-bold px-3 py-2 rounded-xl shadow">
                    <i class="fa-solid fa-pen mr-1"></i> New Post
                </button>
            </div>
            <div id="forumList" class="space-y-3">
                <!-- Dynamically populated -->
            </div>
        </section>

        <!-- TAB 5: SAFETY TOOLS -->
        <section id="tab-tools" class="tab-content p-4 space-y-4">
            <h2 class="font-bold text-lg text-slate-800">Safety & De-escalation Tools</h2>
            
            <!-- Fake Call Generator -->
            <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm space-y-3">
                <div class="flex items-center gap-3">
                    <div class="p-3 bg-indigo-50 text-indigo-600 rounded-xl"><i class="fa-solid fa-phone-volume text-xl"></i></div>
                    <div>
                        <h3 class="font-bold text-sm">Fake Phone Call</h3>
                        <p class="text-xs text-slate-500">Trigger a realistic incoming call to exit unsafe situations.</p>
                    </div>
                </div>
                <div class="grid grid-cols-3 gap-2">
                    <button onclick="startFakeCallTimer(5)" class="bg-slate-100 hover:bg-slate-200 py-2 rounded-lg text-xs font-bold">In 5 Sec</button>
                    <button onclick="startFakeCallTimer(15)" class="bg-slate-100 hover:bg-slate-200 py-2 rounded-lg text-xs font-bold">In 15 Sec</button>
                    <button onclick="startFakeCallTimer(30)" class="bg-slate-100 hover:bg-slate-200 py-2 rounded-lg text-xs font-bold">In 30 Sec</button>
                </div>
            </div>

            <!-- SafeWalk Check-In Timer -->
            <div class="bg-white p-4 rounded-2xl border border-slate-200 shadow-sm space-y-3">
                <div class="flex items-center gap-3">
                    <div class="p-3 bg-emerald-50 text-emerald-600 rounded-xl"><i class="fa-solid fa-stopwatch text-xl"></i></div>
                    <div>
                        <h3 class="font-bold text-sm">SafeWalk Check-In Timer</h3>
                        <p class="text-xs text-slate-500">Triggers an emergency SOS if you don't check in before time expires.</p>
                    </div>
                </div>
                <div class="flex gap-2">
                    <input type="number" id="walkMinutes" placeholder="Minutes (e.g. 15)" class="w-full border border-slate-300 rounded-xl px-3 py-2 text-xs">
                    <button onclick="startSafeWalk()" class="bg-emerald-600 text-white px-4 py-2 rounded-xl text-xs font-bold shadow">Start</button>
                </div>
                <p id="safeWalkStatus" class="text-xs font-bold text-rose-600"></p>
            </div>
        </section>

    </main>

    <!-- FAKE CALL SCREEN OVERLAY -->
    <div id="fakeCallScreen" class="fixed inset-0 bg-slate-900 text-white hidden z-50 flex-col justify-between p-8 text-center">
        <div class="pt-12 space-y-2">
            <p class="text-xs uppercase tracking-widest text-slate-400">Incoming Call</p>
            <h2 class="text-3xl font-bold">Mom</h2>
            <p class="text-sm text-slate-400">Mobile +1 (555) 019-2831</p>
        </div>
        <div class="flex justify-around pb-12">
            <button onclick="endFakeCall()" class="w-16 h-16 bg-red-600 rounded-full flex items-center justify-center text-2xl shadow-lg"><i class="fa-solid fa-phone-slash"></i></button>
            <button onclick="endFakeCall()" class="w-16 h-16 bg-emerald-600 rounded-full flex items-center justify-center text-2xl shadow-lg animate-bounce"><i class="fa-solid fa-phone"></i></button>
        </div>
    </div>

    <!-- INCIDENT / SAFE BAR REPORT MODAL -->
    <div id="reportModal" class="fixed inset-0 bg-black/60 backdrop-blur-sm hidden z-50 flex items-center justify-center p-4">
        <div class="bg-white w-full max-w-sm rounded-2xl p-5 space-y-4">
            <h3 class="font-bold text-base text-slate-800">Add Safety Pin</h3>
            <select id="reportCategory" class="w-full border border-slate-300 rounded-xl p-2.5 text-xs">
                <option value="Safe Bar / Women-Friendly Nightclub">🍸 Safe Bar / Women-Friendly Club</option>
                <option value="Assault / Physical Threat">🚨 Assault / Physical Threat</option>
                <option value="Verbal Harassment Zone">⚠️ Verbal Harassment Zone</option>
                <option value="Poor Lighting / Unsafe Area">💡 Poor Lighting / Unsafe Area</option>
                <option value="Verified Safe Haven">🛡️ Verified Safe Haven / Business</option>
            </select>
            <textarea id="reportDetails" placeholder="Provide details (e.g. well-lit staff, bouncer verified, incident details)..." class="w-full border border-slate-300 rounded-xl p-2.5 text-xs h-24"></textarea>
            <div class="flex gap-2">
                <button onclick="closeReportModal()" class="w-1/2 py-2 text-xs font-bold text-slate-600 bg-slate-100 rounded-xl">Cancel</button>
                <button onclick="submitIncidentReport()" class="w-1/2 py-2 text-xs font-bold text-white bg-rose-600 rounded-xl">Save Pin</button>
            </div>
        </div>
    </div>

    <!-- RIDE MODAL -->
    <div id="rideModal" class="fixed inset-0 bg-black/60 backdrop-blur-sm hidden z-50 flex items-center justify-center p-4">
        <div class="bg-white w-full max-w-sm rounded-2xl p-5 space-y-3">
            <h3 class="font-bold text-base text-slate-800">Post Ride Offer or Request</h3>
            <select id="rideType" class="w-full border border-slate-300 rounded-xl p-2 text-xs">
                <option value="Offering a Ride">Offering a Ride (Driver)</option>
                <option value="Requesting a Ride">Requesting a Ride (Passenger)</option>
            </select>
            <input type="text" id="rideFrom" placeholder="Starting location" class="w-full border border-slate-300 rounded-xl p-2 text-xs">
            <input type="text" id="rideTo" placeholder="Destination" class="w-full border border-slate-300 rounded-xl p-2 text-xs">
            <input type="text" id="rideContact" placeholder="Contact Info (Phone or Social handle)" class="w-full border border-slate-300 rounded-xl p-2 text-xs">
            <div class="flex gap-2 pt-2">
                <button onclick="closeRideModal()" class="w-1/2 py-2 text-xs font-bold text-slate-600 bg-slate-100 rounded-xl">Cancel</button>
                <button onclick="submitRide()" class="w-1/2 py-2 text-xs font-bold text-white bg-rose-600 rounded-xl">Post Ride</button>
            </div>
        </div>
    </div>

    <!-- FORUM MODAL -->
    <div id="forumModal" class="fixed inset-0 bg-black/60 backdrop-blur-sm hidden z-50 flex items-center justify-center p-4">
        <div class="bg-white w-full max-w-sm rounded-2xl p-5 space-y-3">
            <h3 class="font-bold text-base text-slate-800">New Advice Post</h3>
            <input type="text" id="forumTitle" placeholder="Post Title" class="w-full border border-slate-300 rounded-xl p-2 text-xs">
            <textarea id="forumBody" placeholder="Share advice, warning, or ask for opinions..." class="w-full border border-slate-300 rounded-xl p-2 text-xs h-24"></textarea>
            <div class="flex gap-2">
                <button onclick="closeForumModal()" class="w-1/2 py-2 text-xs font-bold text-slate-600 bg-slate-100 rounded-xl">Cancel</button>
                <button onclick="submitForumPost()" class="w-1/2 py-2 text-xs font-bold text-white bg-rose-600 rounded-xl">Publish</button>
            </div>
        </div>
    </div>

    <!-- Bottom Navigation Bar -->
    <nav class="fixed bottom-0 left-0 right-0 bg-white border-t border-slate-200 z-40">
        <div class="max-w-md mx-auto grid grid-cols-5 text-center text-slate-500 py-2">
            <button onclick="switchTab('sos')" class="nav-btn text-rose-600 flex flex-col items-center">
                <i class="fa-solid fa-shield-cat text-lg"></i><span class="text-[10px] mt-1 font-bold">SOS</span>
            </button>
            <button onclick="switchTab('map')" class="nav-btn flex flex-col items-center">
                <i class="fa-solid fa-map-location-dot text-lg"></i><span class="text-[10px] mt-1">Map</span>
            </button>
            <button onclick="switchTab('rides')" class="nav-btn flex flex-col items-center">
                <i class="fa-solid fa-car-side text-lg"></i><span class="text-[10px] mt-1">Rides</span>
            </button>
            <button onclick="switchTab('forum')" class="nav-btn flex flex-col items-center">
                <i class="fa-solid fa-comments text-lg"></i><span class="text-[10px] mt-1">Advice</span>
            </button>
            <button onclick="switchTab('tools')" class="nav-btn flex flex-col items-center">
                <i class="fa-solid fa-toolbox text-lg"></i><span class="text-[10px] mt-1">Tools</span>
            </button>
        </div>
    </nav>

    <!-- JavaScript Application Engine -->
    <script>
        let leafletMap = null;
        let userMarker = null;
        let currentLat = 32.6521;
        let currentLng = -83.7502;
        let sirenAudioCtx = null;
        let sirenOscillator = null;
        let safeWalkInterval = null;

        // Persistent Storage
        let incidents = JSON.parse(localStorage.getItem('her_incidents') || '[]');
        let rides = JSON.parse(localStorage.getItem('her_rides') || '[]');
        let forumPosts = JSON.parse(localStorage.getItem('her_forum') || '[]');

        window.onload = function() {
            initLocation();
            loadSavedContacts();
            checkDriverStatus();
            renderRides();
            renderForum();
        };

        // Tab Navigation
        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
            document.getElementById('tab-' + tabId).classList.add('active');
            
            if (tabId === 'map') {
                setTimeout(() => { initMap(); }, 200);
            }
        }

        // GPS Location
        function initLocation() {
            if ("geolocation" in navigator) {
                navigator.geolocation.getCurrentPosition(position => {
                    currentLat = position.coords.latitude;
                    currentLng = position.coords.longitude;
                    updateSMSLink();
                    if (leafletMap) {
                        leafletMap.setView([currentLat, currentLng], 14);
                        if (userMarker) userMarker.setLatLng([currentLat, currentLng]);
                    }
                }, err => console.log("Geolocation error:", err), { enableHighAccuracy: true });
            }
        }

        // Emergency Contacts Management
        function saveAllContacts() {
            const c1 = document.getElementById('contactPhone1').value.trim();
            const c2 = document.getElementById('contactPhone2').value.trim();
            const c3 = document.getElementById('contactPhone3').value.trim();

            const contacts = [c1, c2, c3].filter(n => n.length > 0);
            localStorage.setItem('her_contacts', JSON.stringify(contacts));

            document.getElementById('savedContactsStatus').innerText = `✓ ${contacts.length} Contact(s) Active`;
            updateSMSLink();
        }

        function loadSavedContacts() {
            const saved = JSON.parse(localStorage.getItem('her_contacts') || '[]');
            if (saved[0]) document.getElementById('contactPhone1').value = saved[0];
            if (saved[1]) document.getElementById('contactPhone2').value = saved[1];
            if (saved[2]) document.getElementById('contactPhone3').value = saved[2];
            
            if (saved.length > 0) {
                document.getElementById('savedContactsStatus').innerText = `✓ ${saved.length} Contact(s) Active`;
            }
            updateSMSLink();
        }

        function updateSMSLink() {
            const contacts = JSON.parse(localStorage.getItem('her_contacts') || '[]');
            const phoneList = contacts.join(',');
            const mapUrl = `https://maps.google.com/?q=${currentLat},${currentLng}`;
            const msg = encodeURIComponent(`EMERGENCY SOS! I need immediate help. My GPS location: ${mapUrl}`);
            document.getElementById('smsEmergencyLink').href = `sms:${phoneList}?body=${msg}`;
        }

        // Emergency SOS Triggers
        function triggerQuickSOS() {
            triggerFullSOS();
        }

        function triggerFullSOS() {
            updateSMSLink();
            toggleSiren(true);
            const confirm911 = confirm("SOS ACTIVATED!\n\nClick OK to call 911 immediately, or Cancel to send group text alerts to your 3 emergency contacts.");
            if (confirm911) {
                window.location.href = "tel:911";
            } else {
                window.location.href = document.getElementById('smsEmergencyLink').href;
            }
        }

        function toggleSiren(forceStart = false) {
            if (sirenOscillator) {
                sirenOscillator.stop();
                sirenOscillator = null;
                document.getElementById('sirenText').innerText = "Loud Siren";
                return;
            }
            sirenAudioCtx = new (window.AudioContext || window.webkitAudioContext)();
            sirenOscillator = sirenAudioCtx.createOscillator();
            const gain = sirenAudioCtx.createGain();
            sirenOscillator.type = 'sawtooth';
            sirenOscillator.frequency.setValueAtTime(800, sirenAudioCtx.currentTime);
            sirenOscillator.frequency.exponentialRampToValueAtTime(400, sirenAudioCtx.currentTime + 0.5);
            
            sirenOscillator.connect(gain);
            gain.connect(sirenAudioCtx.destination);
            sirenOscillator.start();
            document.getElementById('sirenText').innerText = "STOP SIREN";
        }

        // Leaflet Interactive Safety Map + Star Rating + Auto-Kick Logic
        function initMap() {
            if (leafletMap) return;
            leafletMap = L.map('map').setView([currentLat, currentLng], 14);
            L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
                attribution: '© OpenStreetMap contributors'
            }).addTo(leafletMap);

            userMarker = L.marker([currentLat, currentLng]).addTo(leafletMap)
                .bindPopup("<b>Your Current Location</b>").openPopup();

            // Auto-kick places below 3.0 stars
            let activeIncidents = incidents.filter(inc => {
                if (!inc.category.includes('Safe') && !inc.category.includes('Bar')) return true;
                const ratings = inc.ratings || [5];
                const avg = (ratings.reduce((a, b) => a + b, 0) / ratings.length);
                return avg >= 3.0;
            });

            localStorage.setItem('her_incidents', JSON.stringify(activeIncidents));

            // Render pins
            activeIncidents.forEach((inc, index) => {
                const isSafeHaven = inc.category.includes('Safe') || inc.category.includes('Bar');
                const ratings = inc.ratings || [5];
                const avg = (ratings.reduce((a, b) => a + b, 0) / ratings.length).toFixed(1);

                const popupContent = `
                    <div class="p-1 space-y-2 text-slate-800">
                        <div class="font-bold text-xs">${inc.category}</div>
                        <div class="text-[11px] text-slate-600">${inc.details}</div>
                        ${isSafeHaven ? `
                            <div class="border-t border-slate-200 pt-2 space-y-1">
                                <div class="flex items-center justify-between text-xs">
                                    <span class="font-bold text-amber-500">★ ${avg} / 5.0</span>
                                    <span class="text-[10px] text-slate-400">(${ratings.length} reviews)</span>
                                </div>
                                <div class="text-[10px] text-slate-500 font-semibold">Rate Safety:</div>
                                <div class="flex gap-1.5 text-xs text-amber-500 font-bold cursor-pointer pt-0.5">
                                    <button onclick="ratePlace(${index}, 1)" class="bg-slate-100 px-1.5 py-0.5 rounded">★1</button>
                                    <button onclick="ratePlace(${index}, 2)" class="bg-slate-100 px-1.5 py-0.5 rounded">★2</button>
                                    <button onclick="ratePlace(${index}, 3)" class="bg-slate-100 px-1.5 py-0.5 rounded">★3</button>
                                    <button onclick="ratePlace(${index}, 4)" class="bg-slate-100 px-1.5 py-0.5 rounded">★4</button>
                                    <button onclick="ratePlace(${index}, 5)" class="bg-slate-100 px-1.5 py-0.5 rounded">★5</button>
                                </div>
                            </div>
                        ` : ''}
                    </div>
                `;

                L.circleMarker([inc.lat, inc.lng], {
                    color: isSafeHaven ? '#059669' : '#dc2626',
                    radius: 9
                }).addTo(leafletMap).bindPopup(popupContent);
            });
        }

        function ratePlace(index, stars) {
            let incidents = JSON.parse(localStorage.getItem('her_incidents') || '[]');
            if (!incidents[index]) return;

            if (!incidents[index].ratings) incidents[index].ratings = [5];
            incidents[index].ratings.push(stars);

            const sum = incidents[index].ratings.reduce((a, b) => a + b, 0);
            const avg = (sum / incidents[index].ratings.length).toFixed(1);

            if (parseFloat(avg) < 3.0) {
                const placeName = incidents[index].category;
                incidents.splice(index, 1);
                localStorage.setItem('her_incidents', JSON.stringify(incidents));
                alert(`🚨 AUTO-KICK ALERT: ${placeName} rating fell to ${avg}/5.0 stars and was automatically removed from the safety map.`);
                location.reload();
                return;
            }

            localStorage.setItem('her_incidents', JSON.stringify(incidents));
            alert(`Rating updated! ${incidents[index].category} now holds a ${avg} / 5.0 star score.`);
            location.reload();
        }

        function openReportModal() { document.getElementById('reportModal').classList.remove('hidden'); }
        function closeReportModal() { document.getElementById('reportModal').classList.add('hidden'); }

        function submitIncidentReport() {
            const category = document.getElementById('reportCategory').value;
            const details = document.getElementById('reportDetails').value;
            
            const newIncident = { lat: currentLat, lng: currentLng, category, details, ratings: [5], date: new Date().toLocaleDateString() };
            incidents.push(newIncident);
            localStorage.setItem('her_incidents', JSON.stringify(incidents));

            closeReportModal();
            document.getElementById('reportDetails').value = '';
            location.reload();
        }

        // SheSafe Driver ID Verification & Rides
        function startDriverVerification() {
            const stripeIdentityUrl = "YOUR_STRIPE_IDENTITY_VERIFICATION_LINK";
            if (stripeIdentityUrl === "YOUR_STRIPE_IDENTITY_VERIFICATION_LINK") {
                const devVerify = confirm("SheSafe Government ID Verification:\n\nIn live production, this opens Stripe Identity to scan driver's licenses.\n\nClick OK to simulate passing ID verification for testing.");
                if (devVerify) {
                    localStorage.setItem('shesafe_driver_verified', 'true');
                    checkDriverStatus();
                }
            } else {
                window.open(stripeIdentityUrl, '_blank');
            }
        }

        function checkDriverStatus() {
            const isVerified = localStorage.getItem('shesafe_driver_verified') === 'true';
            const badge = document.getElementById('driverStatusBadge');
            if (isVerified && badge) {
                badge.innerText = "✓ SheSafe Verified Driver";
                badge.className = "bg-emerald-500/20 text-emerald-300 text-[10px] font-bold px-2 py-0.5 rounded-full border border-emerald-500/30";
            }
        }

        function openRideModal() { document.getElementById('rideModal').classList.remove('hidden'); }
        function closeRideModal() { document.getElementById('rideModal').classList.add('hidden'); }

        function submitRide() {
            const type = document.getElementById('rideType').value;
            const isVerified = localStorage.getItem('shesafe_driver_verified') === 'true';

            if (type.includes('Offering') && !isVerified) {
                alert("Security Requirement: You must verify your ID as a SheSafe Driver before offering rides to women.");
                startDriverVerification();
                return;
            }

            const from = document.getElementById('rideFrom').value;
            const to = document.getElementById('rideTo').value;
            const contact = document.getElementById('rideContact').value;

            rides.unshift({ 
                type: isVerified && type.includes('Offering') ? "Offering a Ride (SheSafe Verified Driver)" : type, 
                from, 
                to, 
                contact, 
                date: new Date().toLocaleDateString() 
            });

            localStorage.setItem('her_rides', JSON.stringify(rides));
            renderRides();
            closeRideModal();
        }

        function renderRides() {
            const container = document.getElementById('ridesList');
            if (rides.length === 0) {
                container.innerHTML = '<p class="text-xs text-slate-400 text-center py-6">No ride requests or offers posted yet.</p>';
                return;
            }
            container.innerHTML = rides.map(r => `
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 shadow-sm space-y-1">
                    <div class="flex justify-between items-center">
                        <span class="text-[10px] font-bold uppercase px-2 py-0.5 rounded-full ${r.type.includes('Offering') ? 'bg-emerald-100 text-emerald-700' : 'bg-rose-100 text-rose-700'}">${r.type}</span>
                        <span class="text-[10px] text-slate-400">${r.date}</span>
                    </div>
                    <p class="text-xs font-bold text-slate-800">${r.from} ➔ ${r.to}</p>
                    <p class="text-xs text-rose-600 font-medium"><i class="fa-solid fa-address-book mr-1"></i>Contact: ${r.contact}</p>
                </div>
            `).join('');
        }

        // Forum Section
        function openForumModal() { document.getElementById('forumModal').classList.remove('hidden'); }
        function closeForumModal() { document.getElementById('forumModal').classList.add('hidden'); }

        function submitForumPost() {
            const title = document.getElementById('forumTitle').value;
            const body = document.getElementById('forumBody').value;

            forumPosts.unshift({ title, body, date: new Date().toLocaleDateString() });
            localStorage.setItem('her_forum', JSON.stringify(forumPosts));
            renderForum();
            closeForumModal();
        }

        function renderForum() {
            const container = document.getElementById('forumList');
            if (forumPosts.length === 0) {
                container.innerHTML = '<p class="text-xs text-slate-400 text-center py-6">No community posts yet.</p>';
                return;
            }
            container.innerHTML = forumPosts.map(f => `
                <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm space-y-2">
                    <h3 class="font-bold text-sm text-slate-800">${f.title}</h3>
                    <p class="text-xs text-slate-600">${f.body}</p>
                    <div class="flex justify-between items-center pt-2 text-[10px] text-slate-400">
                        <span><i class="fa-solid fa-user-check text-emerald-500 mr-1"></i> Community Post</span>
                        <span>${f.date}</span>
                    </div>
                </div>
            `).join('');
        }

        // Fake Call Overlay Timer
        function startFakeCallTimer(seconds) {
            alert(`Fake incoming call scheduled in ${seconds} seconds.`);
            setTimeout(() => {
                document.getElementById('fakeCallScreen').classList.remove('hidden');
                document.getElementById('fakeCallScreen').classList.add('flex');
            }, seconds * 1000);
        }

        function endFakeCall() {
            document.getElementById('fakeCallScreen').classList.add('hidden');
            document.getElementById('fakeCallScreen').classList.remove('flex');
        }

        // SafeWalk Check-in Timer
        function startSafeWalk() {
            const mins = parseInt(document.getElementById('walkMinutes').value);
            if (!mins) return;
            let secondsLeft = mins * 60;
            const statusEl = document.getElementById('safeWalkStatus');

            if (safeWalkInterval) clearInterval(safeWalkInterval);

            safeWalkInterval = setInterval(() => {
                secondsLeft--;
                const m = Math.floor(secondsLeft / 60);
                const s = secondsLeft % 60;
                statusEl.innerText = `SafeWalk Active: ${m}m ${s}s remaining`;

                if (secondsLeft <= 0) {
                    clearInterval(safeWalkInterval);
                    statusEl.innerText = "EXPIRED - DISPATCHING SOS!";
                    triggerFullSOS();
                }
            }, 1000);
        }
    </script>
</body>
</html>
