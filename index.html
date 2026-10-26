<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Habit Tracker - Modern</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0f1419;
    --card-bg: #1a1f2e;
    --text-main: #ffffff;
    --text-sub: #9aa0a6;
    --accent: #00e5ff;
    --accent-hover: #00b8d4;
    --danger: #ff6b4a;
    --success: #4aaa4a;
    --warning: #f1c40f;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body { 
    background-color: var(--bg); 
    color: var(--text-main); 
    font-family: 'Inter', sans-serif; 
    transition: background-color 0.3s, color 0.3s;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  /* Light Mode */
  body.light-mode { 
    --bg: #f0f2f5; 
    --card-bg: #ffffff; 
    --text-main: #1a1f2e; 
    --text-sub: #6b7280;
  }

  .container { width: 100%; max-width: 500px; padding: 20px; }

  /* Icons */
  .svg-icon { width: 20px; height: 20px; stroke: currentColor; fill: none; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round; flex-shrink: 0; }
  .icon-btn { background: transparent; border: none; color: var(--text-sub); cursor: pointer; padding: 6px; display: flex; align-items: center; justify-content: center; border-radius: 8px; transition: 0.2s; }
  .icon-btn:hover { background: rgba(255,255,255,0.1); color: var(--text-main); transform: scale(1.1); }
  body.light-mode .icon-btn:hover { background: rgba(0,0,0,0.05); }
  .icon-btn.delete:hover { color: var(--danger); }

  /* Header */
  .title-container { display: flex; align-items: center; justify-content: center; gap: 12px; margin-top: 20px; margin-bottom: 20px; }
  h1 { font-size: 32px; font-weight: 800; letter-spacing: -1px; }
  
  /* Top Actions */
  .top-actions { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; }
  #themeButton { background: var(--card-bg); border: 1px solid #2a3142; color: var(--text-main); padding: 10px 16px; border-radius: 20px; font-size: 13px; font-weight: 600; cursor: pointer; transition: 0.2s; display: flex; align-items: center; gap: 8px; }
  body.light-mode #themeButton { border-color: #d1d5db; }
  #themeButton:hover { border-color: var(--accent); }

  /* Date & Streak Boxes */
  #dateBox, #streakBox {
    background: var(--card-bg);
    border: 1px solid #2a3142;
    border-radius: 16px;
    padding: 16px;
    margin-bottom: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-weight: 600;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
  }
  body.light-mode #dateBox, body.light-mode #streakBox { border-color: #e5e7eb; }

  #dateCheckButton { background: #2a3142; color: var(--text-main); border: none; padding: 10px 16px; border-radius: 10px; font-weight: bold; cursor: pointer; transition: 0.3s; display: flex; align-items: center; gap: 8px; }
  #dateCheckButton.checked { background: linear-gradient(135deg, #00e5ff, #0088cc); color: #000; }
  
  #streakBox { color: #ff6b4a; font-size: 18px; justify-content: center; gap: 8px; }

  /* Main Card */
  .card { 
    background-color: var(--card-bg); 
    padding: 25px; 
    border-radius: 20px; 
    border: 1px solid #2a3142;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  }
  body.light-mode .card { border-color: #e5e7eb; }
  
  h2 { text-align: center; font-size: 24px; margin-bottom: 15px; }
  .completed { text-align: center; color: var(--text-sub); font-size: 14px; margin-bottom: 5px; }
  #progressText { text-align: center; color: var(--accent); font-weight: bold; font-size: 16px; margin-bottom: 15px; }
  
  .progress-container { width: 100%; height: 12px; background-color: #2a3142; border-radius: 10px; overflow: hidden; margin-bottom: 25px; }
  body.light-mode .progress-container { background-color: #e5e7eb; }
  #progressBar { width: 0%; height: 100%; background: linear-gradient(90deg, var(--accent), #0088cc); border-radius: 10px; transition: width 0.4s ease; }

  /* Buttons Group */
  .button-group { display: flex; gap: 10px; justify-content: center; margin-bottom: 20px; }
  .button-group button { flex: 1; padding: 12px; border: none; border-radius: 12px; font-weight: bold; font-size: 14px; cursor: pointer; transition: 0.2s; display: flex; justify-content: center; align-items: center; gap: 6px; }
  #resetButton { background: #2a3142; color: #fff; }
  body.light-mode #resetButton { background: #e5e7eb; color: #1a1f2e; }
  #addHabitButton { background: linear-gradient(135deg, #4a9eff, #2a7fdb); color: white; }
  #checkAllButton { background: linear-gradient(135deg, #4aaa4a, #2ecc71); color: white; }
  .button-group button:hover { transform: translateY(-2px); box-shadow: 0 5px 15px rgba(0,0,0,0.2); }

  /* Habit List */
  #habitList { list-style: none; display: flex; flex-direction: column; gap: 10px; }
  #habitList li { 
    display: flex; align-items: center; gap: 12px; padding: 12px 15px; 
    background: #0f1419; border: 1px solid #2a3142; border-radius: 12px; 
    transition: 0.3s; 
  }
  body.light-mode #habitList li { background: #f8f9fa; border-color: #e5e7eb; }

  /* Empty State */
  #emptyState {
    display: none;
    text-align: center;
    color: var(--text-sub);
    padding: 30px 10px;
    font-size: 15px;
    font-weight: 500;
  }

  /* Custom Checkbox */
  #habitList li input[type="checkbox"] { 
    appearance: none; width: 24px; height: 24px; border-radius: 6px; 
    background: #2a3142; cursor: pointer; position: relative; flex-shrink: 0; transition: 0.2s;
  }
  body.light-mode #habitList li input[type="checkbox"] { background: #d1d5db; }
  #habitList li input[type="checkbox"]:checked { background: var(--accent); }
  #habitList li input[type="checkbox"]:checked::after { 
    content: "✓"; position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); 
    color: #000; font-weight: bold; font-size: 16px; 
  }

  .habit-text { flex: 1; font-size: 15px; font-weight: 500; transition: 0.3s; }
  #habitList li input:checked ~ .habit-text { text-decoration: line-through; color: var(--text-sub); }

  /* Modals */
  .modal-overlay { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.8); backdrop-filter: blur(5px); z-index: 1000; justify-content: center; align-items: center; padding: 20px; }
  .modal-overlay.active { display: flex; }
  .modal-box { background: var(--card-bg); padding: 25px; border-radius: 20px; width: 100%; max-width: 400px; border: 1px solid #2a3142; box-shadow: 0 10px 40px rgba(0,0,0,0.5); }
  .modal-box h3 { margin: 0 0 10px 0; text-align: center; font-size: 20px; display: flex; align-items: center; justify-content: center; gap: 8px; }
  .modal-box p { text-align: center; color: var(--text-sub); font-size: 14px; margin-bottom: 20px; }
  #modalInput { width: 100%; padding: 14px; background: var(--bg); border: 1px solid #2a3142; border-radius: 12px; color: var(--text-main); font-size: 15px; outline: none; font-family: inherit; }
  body.light-mode #modalInput { border-color: #d1d5db; }
  #modalInput:focus { border-color: var(--accent); }
  .modal-buttons { display: flex; gap: 10px; margin-top: 20px; }
  .modal-btn { flex: 1; padding: 14px; border: none; border-radius: 12px; font-size: 15px; font-weight: bold; cursor: pointer; transition: 0.2s; }
  .modal-btn.cancel { background: #2a3142; color: var(--text-main); }
  body.light-mode .modal-btn.cancel { background: #e5e7eb; color: #1a1f2e; }
  .modal-btn.save { background: var(--accent); color: #000; }
  .modal-btn.delete { background: var(--danger); color: #fff; }
  .modal-btn:hover { transform: translateY(-2px); }

  /* Confetti */
  .confetti-piece { position: fixed; top: -20px; width: 10px; height: 10px; z-index: 9999; animation: fall 1.5s linear forwards; }
  @keyframes fall { 0% { transform: translateY(0) rotate(0deg); opacity: 1; } 100% { transform: translateY(105vh) rotate(720deg); opacity: 0; } }

  /* Toast Notification */
  #toastContainer {
    position: fixed; top: 20px; left: 50%; transform: translateX(-50%); z-index: 99999;
    display: flex; flex-direction: column; gap: 10px; pointer-events: none;
  }
  .toast {
    background: var(--card-bg); color: var(--text-main); padding: 12px 20px; border-radius: 12px;
    font-size: 14px; font-weight: 600; box-shadow: 0 8px 25px rgba(0,0,0,0.4);
    border-left: 4px solid var(--accent); display: flex; align-items: center; gap: 10px;
    opacity: 0; transform: translateY(-20px); transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55); min-width: 200px;
  }
  .toast.show { opacity: 1; transform: translateY(0); }
  .toast.success { border-left-color: var(--success); }
  .toast.error { border-left-color: var(--danger); }
  .toast.info { border-left-color: var(--accent); }
  .toast.warning { border-left-color: var(--warning); }
  
  .toast-icon { width: 20px; height: 20px; flex-shrink: 0; }
  .toast.success .toast-icon { stroke: var(--success); }
  .toast.error .toast-icon { stroke: var(--danger); }
  .toast.info .toast-icon { stroke: var(--accent); }
  .toast.warning .toast-icon { stroke: var(--warning); }
</style>
</head>
<body>
  <div id="toastContainer"></div>

  <div class="container">
    <div class="title-container">
      <h1 id="mainTitle">Habit Tracker</h1>
      <button id="editTitleButton" class="icon-btn" title="Edit Title">
        <svg class="svg-icon" viewBox="0 0 24 24"><path d="M17 3a2.828 2.828 0 1 1 4 4L7.5 20.5 2 22l1.5-5.5L17 3z"></path></svg>
      </button>
    </div>
    
    <div class="top-actions">
      <button id="themeButton">
        <svg id="themeIcon" class="svg-icon" viewBox="0 0 24 24"><circle cx="12" cy="12" r="5"></circle><line x1="12" y1="1" x2="12" y2="3"></line><line x1="12" y1="21" x2="12" y2="23"></line><line x1="4.22" y1="4.22" x2="5.64" y2="5.64"></line><line x1="18.36" y1="18.36" x2="19.78" y2="19.78"></line><line x1="1" y1="12" x2="3" y2="12"></line><line x1="21" y1="12" x2="23" y2="12"></line><line x1="4.22" y1="19.78" x2="5.64" y2="18.36"></line><line x1="18.36" y1="5.64" x2="19.78" y2="4.22"></line></svg>
        <span id="themeText">Light Mode</span>
      </button>
    </div>
    
    <div id="dateBox">
      <span id="currentDate">Loading...</span>
      <button id="dateCheckButton" title="Mark today as complete">
        <svg id="dateIcon" class="svg-icon" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect></svg>
        <span id="dateText">Mark Done</span>
      </button>
    </div>
    
    <div id="streakBox">
      <svg class="svg-icon" style="stroke: #ff6b4a;" viewBox="0 0 24 24"><path d="M8.5 14.5A2.5 2.5 0 0 0 11 12c0-1.38-.5-2-1-3-1.072-2.143-.224-4.054 2-6 .5 2.5 2 4.9 4 6.5 2 1.6 3 3.5 3 5.5a7 7 0 1 1-14 0c0-1.153.433-2.294 1-3a2.5 2.5 0 0 0 2.5 2.5z"></path></svg>
      Current Streak: <span id="streakCount">0</span> Days
    </div>
    
    <div class="card">
      <h2>Daily Habits</h2>
      <p class="completed">Completed: <span id="count">0</span></p>
      <p id="progressText">Progress: 0%</p>
      <div class="progress-container">
        <div id="progressBar"></div>
      </div>
      <div class="button-group">
        <button id="resetButton" type="button">Reset</button>
        <button id="addHabitButton" type="button">+Add</button>
        <button id="checkAllButton" type="button">✓ All</button>
      </div>
      <ul id="habitList"></ul>
      <div id="emptyState">
        No Habits Yet.! Click "+Add" to get started!
      </div>
    </div>
  </div>

  <!-- Add/Edit Modal -->
  <div id="habitModal" class="modal-overlay">
    <div class="modal-box">
      <h3 id="modalTitle">Add New Habit</h3>
      <input type="text" id="modalInput" placeholder="Type habit name..." autocomplete="off">
      <div class="modal-buttons">
        <button id="modalCancel" class="modal-btn cancel">Cancel</button>
        <button id="modalSave" class="modal-btn save">Save</button>
      </div>
    </div>
  </div>

  <!-- Custom Delete Modal -->
  <div id="deleteModal" class="modal-overlay">
    <div class="modal-box">
      <h3 style="color: var(--danger);">
        <svg class="svg-icon" viewBox="0 0 24 24"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"></path><line x1="12" y1="9" x2="12" y2="13"></line><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
        Delete Habit?
      </h3>
      <p>Are you sure you want to delete this habit? This action cannot be undone.</p>
      <div class="modal-buttons">
        <button id="deleteCancel" class="modal-btn cancel">Cancel</button>
        <button id="deleteConfirm" class="modal-btn delete">Delete</button>
      </div>
    </div>
  </div>

<script>
// ===== Default Habits =====
let habits = JSON.parse(localStorage.getItem("habitsListV3")) || [
  "5:00 AM, Wake Up",
  "5:10 AM, Shower",
  "5:30 AM, Read Book",
  "7:00 AM, Workout",
  "9:00 AM, Deep Work"
];

const habitList = document.getElementById("habitList");
const emptyState = document.getElementById("emptyState");
const addHabitButton = document.getElementById("addHabitButton");
const count = document.getElementById("count");
const progressText = document.getElementById("progressText");
const progressBar = document.getElementById("progressBar");
const streakCount = document.getElementById("streakCount");
const resetButton = document.getElementById("resetButton");
const themeButton = document.getElementById("themeButton");
const themeText = document.getElementById("themeText");
const themeIcon = document.getElementById("themeIcon");
let currentCheckboxes = [];

// ===== Toast Notification System =====
function showToast(message, type = 'info') {
  const container = document.getElementById("toastContainer");
  const toast = document.createElement("div");
  toast.className = `toast ${type}`;

  let iconSvg = "";
  if (type === 'success') {
    iconSvg = `<svg class="toast-icon" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>`;
  } else if (type === 'error') {
    iconSvg = `<svg class="toast-icon" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="15" y1="9" x2="9" y2="15"></line><line x1="9" y1="9" x2="15" y2="15"></line></svg>`;
  } else if (type === 'warning') {
    iconSvg = `<svg class="toast-icon" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"></path><line x1="12" y1="9" x2="12" y2="13"></line><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>`;
  } else {
    iconSvg = `<svg class="toast-icon" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="16" x2="12" y2="12"></line><line x1="12" y1="8" x2="12.01" y2="8"></line></svg>`;
  }

  toast.innerHTML = `${iconSvg} <span>${message}</span>`;
  container.appendChild(toast);

  setTimeout(() => toast.classList.add("show"), 10);
  setTimeout(() => {
    toast.classList.remove("show");
    setTimeout(() => toast.remove(), 300);
  }, 2500);
}

// ===== SVG Strings for UI =====
const sunIconStr = `<circle cx="12" cy="12" r="5"></circle><line x1="12" y1="1" x2="12" y2="3"></line><line x1="12" y1="21" x2="12" y2="23"></line><line x1="4.22" y1="4.22" x2="5.64" y2="5.64"></line><line x1="18.36" y1="18.36" x2="19.78" y2="19.78"></line><line x1="1" y1="12" x2="3" y2="12"></line><line x1="21" y1="12" x2="23" y2="12"></line><line x1="4.22" y1="19.78" x2="5.64" y2="18.36"></line><line x1="18.36" y1="5.64" x2="19.78" y2="4.22"></line>`;
const moonIconStr = `<path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path>`;
const checkIconStr = `<polyline points="20 6 9 17 4 12"></polyline>`;
const squareIconStr = `<rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect>`;

// ===== Theme Logic (Persistent) =====
const savedTheme = localStorage.getItem("habitTrackerTheme");
if (savedTheme === "light") {
  document.body.classList.add("light-mode");
  themeText.textContent = "Dark Mode";
  themeIcon.innerHTML = moonIconStr;
} else {
  document.body.classList.remove("light-mode");
  themeText.textContent = "Light Mode";
  themeIcon.innerHTML = sunIconStr;
}

themeButton.onclick = function() {
  document.body.classList.toggle("light-mode");
  const isLight = document.body.classList.contains("light-mode");
  
  themeText.textContent = isLight ? "Dark Mode" : "Light Mode";
  themeIcon.innerHTML = isLight ? moonIconStr : sunIconStr;
  
  localStorage.setItem("habitTrackerTheme", isLight ? "light" : "dark");
  showToast(isLight ? "Light Mode Enabled" : "Dark Mode Enabled", "info");
};

// ===== Date Functions =====
function getTodayDate() {
  const today = new Date();
  return today.getFullYear() + "-" + String(today.getMonth() + 1).padStart(2, "0") + "-" + String(today.getDate()).padStart(2, "0");
}

function getFormattedDate() {
  const options = { weekday: "long", day: "numeric", month: "short", year: "numeric" };
  return new Date().toLocaleDateString("en-GB", options);
}

// ===== Render =====
function renderHabits() {
  habitList.innerHTML = "";
  currentCheckboxes = [];
  
  // Show Empty State if no habits
  if (habits.length === 0) {
    emptyState.style.display = "block";
    habitList.style.display = "none";
    count.textContent = "0";
    progressText.textContent = "Progress: 0%";
    progressBar.style.width = "0%";
    return;
  } else {
    emptyState.style.display = "none";
    habitList.style.display = "flex";
  }
  
  const editIcon = `<svg class="svg-icon" viewBox="0 0 24 24"><path d="M17 3a2.828 2.828 0 1 1 4 4L7.5 20.5 2 22l1.5-5.5L17 3z"></path></svg>`;
  const trashIcon = `<svg class="svg-icon" viewBox="0 0 24 24"><polyline points="3 6 5 6 21 6"></polyline><path d="M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6m3 0V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"></path><line x1="10" y1="11" x2="10" y2="17"></line><line x1="14" y1="11" x2="14" y2="17"></line></svg>`;

  habits.forEach(function(habitText, index) {
    const li = document.createElement("li");
    
    const checkbox = document.createElement("input");
    checkbox.type = "checkbox";
    checkbox.dataset.index = index;
    currentCheckboxes.push(checkbox);
    
    const span = document.createElement("span");
    span.className = "habit-text";
    span.textContent = habitText;
    
    const editBtn = document.createElement("button");
    editBtn.innerHTML = editIcon;
    editBtn.className = "icon-btn";
    editBtn.title = "Edit";
    editBtn.onclick = () => editHabit(index);
    
    const deleteBtn = document.createElement("button");
    deleteBtn.innerHTML = trashIcon;
    deleteBtn.className = "icon-btn delete";
    deleteBtn.title = "Delete";
    deleteBtn.onclick = () => openDeleteModal(index);
    
    checkbox.onchange = function() {
      saveHabits();
      updateProgress();
      updateStreak();
      autoUpdateDateFromHabits();
      if(checkbox.checked) {
         showToast("Habit checked!", "success");
      }
    };
    
    li.appendChild(checkbox);
    li.appendChild(span);
    li.appendChild(editBtn);
    li.appendChild(deleteBtn);
    habitList.appendChild(li);
  });
  loadHabits();
  autoUpdateDateFromHabits();
}

// ===== Add/Edit Modal =====
const habitModal = document.getElementById("habitModal");
const modalTitle = document.getElementById("modalTitle");
const modalInput = document.getElementById("modalInput");
let modalCallback = null;

function openModal(title, defaultValue, callback) {
  modalTitle.textContent = title;
  modalInput.value = defaultValue;
  modalCallback = callback;
  habitModal.classList.add("active");
  setTimeout(() => modalInput.focus(), 100);
}

function closeModal() {
  habitModal.classList.remove("active");
  modalCallback = null;
}

document.getElementById("modalCancel").onclick = closeModal;
document.getElementById("modalSave").onclick = function() {
  const value = modalInput.value.trim();
  if (value === "") {
    showToast("Please enter a habit name!", "warning");
    return;
  }
  if (modalCallback) {
    modalCallback(value);
    closeModal();
  }
};
modalInput.onkeypress = (e) => { if (e.key === "Enter") document.getElementById("modalSave").click(); };
habitModal.onclick = (e) => { if (e.target === habitModal) closeModal(); };

// ===== Delete Modal Logic =====
const deleteModal = document.getElementById("deleteModal");
let deletingIndex = null;

function openDeleteModal(index) {
  deletingIndex = index;
  deleteModal.classList.add("active");
}

document.getElementById("deleteCancel").onclick = function() {
  deleteModal.classList.remove("active");
  deletingIndex = null;
};

document.getElementById("deleteConfirm").onclick = function() {
  if (deletingIndex !== null) {
    habits.splice(deletingIndex, 1);
    saveHabitList();
    renderHabits();
    updateProgress();
    deleteModal.classList.remove("active");
    deletingIndex = null;
    showToast("Habit deleted!", "info");
  }
};

deleteModal.onclick = (e) => { if (e.target === deleteModal) { deleteModal.classList.remove("active"); deletingIndex = null; } };

// ===== Actions =====
function editHabit(index) {
  openModal("Edit Habit", habits[index], function(newText) {
    habits[index] = newText;
    saveHabitList();
    renderHabits();
    updateProgress();
    showToast("Habit updated!", "success");
  });
}

addHabitButton.onclick = function() {
  openModal("Add New Habit", "", function(newText) {
    habits.push(newText);
    saveHabitList();
    renderHabits();
    updateProgress();
    showToast("Habit added successfully!", "success");
  });
};

// ===== Save/Load =====
function saveHabitList() { localStorage.setItem("habitsListV3", JSON.stringify(habits)); }
function saveHabits() { localStorage.setItem("habits-" + getTodayDate(), JSON.stringify(currentCheckboxes.map(cb => cb.checked))); }
function loadHabits() {
  const saved = JSON.parse(localStorage.getItem("habits-" + getTodayDate()) || "null");
  currentCheckboxes.forEach((cb, i) => { cb.checked = Array.isArray(saved) && saved[i] === true; });
}

// ===== Progress & Streak =====
function checkAllHabitsCompleted() {
  return currentCheckboxes.length > 0 && currentCheckboxes.every(cb => cb.checked);
}

function updateProgress() {
  const total = currentCheckboxes.length;
  const completed = currentCheckboxes.filter(cb => cb.checked).length;
  const percent = total > 0 ? Math.round((completed / total) * 100) : 0;
  count.textContent = completed;
  progressText.textContent = "Progress: " + percent + "%";
  progressBar.style.width = percent + "%";
  
  if (percent === 100 && total > 0) {
    showConfetti();
  }
}

function autoUpdateDateFromHabits() {
  const todayKey = "date-check-" + getTodayDate();
  localStorage.setItem(todayKey, checkAllHabitsCompleted() ? "true" : "false");
  updateDateDisplay();
}

function updateStreak() {
  const today = getTodayDate();
  const lastDate = localStorage.getItem("lastCompletedDate");
  let streak = Number(localStorage.getItem("streak") || 0);
  
  if (checkAllHabitsCompleted()) {
    if (lastDate !== today) {
      const yesterday = new Date();
      yesterday.setDate(yesterday.getDate() - 1);
      const yKey = yesterday.getFullYear() + "-" + String(yesterday.getMonth() + 1).padStart(2, "0") + "-" + String(yesterday.getDate()).padStart(2, "0");
      streak = lastDate === yKey ? streak + 1 : 1;
      localStorage.setItem("streak", String(streak));
      localStorage.setItem("lastCompletedDate", today);
    }
  } else if (lastDate === today) {
    streak = 0;
    localStorage.setItem("streak", "0");
    localStorage.removeItem("lastCompletedDate");
  }
  streakCount.textContent = streak;
}

// ===== Buttons =====
resetButton.onclick = function() {
  if (habits.length === 0) {
    showToast("Please Enter Habits First", "warning");
    return;
  }
  currentCheckboxes.forEach(cb => cb.checked = false);
  saveHabits(); updateProgress(); updateStreak(); autoUpdateDateFromHabits();
  showToast("All habits unchecked.", "info");
};

document.getElementById("checkAllButton").onclick = function() {
  if (habits.length === 0) {
    showToast("Please Enter Habits First", "warning");
    return;
  }
  currentCheckboxes.forEach(cb => cb.checked = true);
  saveHabits(); updateProgress(); updateStreak(); autoUpdateDateFromHabits();
  showToast("All habits checked!", "success");
};

// ===== Title Edit =====
const mainTitle = document.getElementById("mainTitle");
if (localStorage.getItem("customTitle")) mainTitle.textContent = localStorage.getItem("customTitle");
document.getElementById("editTitleButton").onclick = function() {
  openModal("Edit Title", mainTitle.textContent, function(newTitle) {
    mainTitle.textContent = newTitle;
    localStorage.setItem("customTitle", newTitle);
    showToast("Title updated!", "success");
  });
};

// ===== Date Display =====
const dateIcon = document.getElementById("dateIcon");
const dateText = document.getElementById("dateText");

function updateDateDisplay() {
  const isChecked = localStorage.getItem("date-check-" + getTodayDate()) === "true";
  const btn = document.getElementById("dateCheckButton");
  document.getElementById("currentDate").textContent = getFormattedDate();
  
  if (isChecked) {
    dateIcon.innerHTML = checkIconStr;
    dateText.textContent = "Done";
    btn.classList.add("checked");
  } else {
    dateIcon.innerHTML = squareIconStr;
    dateText.textContent = "Mark Done";
    btn.classList.remove("checked");
  }
}

document.getElementById("dateCheckButton").onclick = function() {
  if (habits.length === 0) {
    showToast("Please Add Habits First", "warning");
    return;
  }
  
  const todayKey = "date-check-" + getTodayDate();
  const isChecked = localStorage.getItem(todayKey) === "true";
  localStorage.setItem(todayKey, isChecked ? "false" : "true");
  updateDateDisplay();
  
  if(!isChecked) {
      showToast("Day marked as Done!", "success");
  } else {
      showToast("Day unchecked.", "info");
  }
};

// ===== Confetti Effect =====
function showConfetti() {
  const colors = ['#00e5ff', '#4a9eff', '#ff6b4a', '#d6a1f0', '#4aaa4a', '#f1c40f'];
  for (let i = 0; i < 50; i++) {
    const confetti = document.createElement('div');
    confetti.classList.add('confetti-piece');
    confetti.style.left = Math.random() * 100 + 'vw';
    confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
    confetti.style.animationDuration = (Math.random() * 1 + 1) + 's'; 
    document.body.appendChild(confetti);
    setTimeout(() => confetti.remove(), 2000);
  }
}

// ===== Start =====
renderHabits();
updateProgress();
updateStreak();
updateDateDisplay();
</script>
</body>
</html>
