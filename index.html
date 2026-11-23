<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KLA Daily tracking</title>
  <style>
    :root {
      --primary: #16a34a;
      --primary-hover: #15803d;
      --secondary: #2563eb;
      --secondary-hover: #1d4ed8;
      --bg: #f3f4f6;
      --card-bg: #ffffff;
      --text: #1f2937;
      --muted: #6b7280;
      --border: #d1d5db;
      --danger: #dc2626;
    }

    * {
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }

    body {
      margin: 0;
      padding: 20px 14px;
      background-color: var(--bg);
      color: var(--text);
      display: flex;
      justify-content: center;
    }

    .container {
      width: 100%;
      max-width: 520px;
      background: var(--card-bg);
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.06);
      padding: 24px 20px;
    }

    .header {
      border-bottom: 1px solid #e5e7eb;
      padding-bottom: 14px;
      margin-bottom: 20px;
    }

    .header h1 {
      margin: 0 0 6px 0;
      font-size: 22px;
      font-weight: 700;
      color: #111827;
    }

    .header p {
      margin: 0;
      font-size: 13px;
      color: var(--muted);
    }

    .form-group {
      margin-bottom: 18px;
    }

    label.field-title {
      display: block;
      font-size: 14px;
      font-weight: 600;
      margin-bottom: 8px;
      color: #374151;
    }

    .req {
      color: var(--danger);
      margin-right: 3px;
    }

    input[type="text"],
    input[type="number"],
    input[type="date"],
    select {
      width: 100%;
      padding: 10px 12px;
      border: 1px solid var(--border);
      border-radius: 8px;
      font-size: 15px;
      background-color: #fff;
      transition: border-color 0.2s;
    }

    input:focus,
    select:focus {
      outline: none;
      border-color: var(--primary);
      box-shadow: 0 0 0 3px rgba(22, 163, 74, 0.12);
    }

    .checkbox-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
    }

    .checkbox-item {
      display: flex;
      align-items: center;
      padding: 9px 12px;
      border: 1px solid var(--border);
      border-radius: 8px;
      cursor: pointer;
      font-size: 14px;
      user-select: none;
      transition: all 0.15s;
    }

    .checkbox-item:hover {
      background-color: #f9fafb;
    }

    .checkbox-item input {
      margin-right: 8px;
      width: 16px;
      height: 16px;
      accent-color: var(--primary);
    }

    .btn-group {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 24px;
    }

    button {
      width: 100%;
      padding: 12px 16px;
      border: none;
      border-radius: 8px;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      transition: background-color 0.2s, transform 0.05s;
    }

    button:active {
      transform: scale(0.99);
    }

    .btn-whatsapp {
      background-color: var(--primary);
      color: #ffffff;
    }

    .btn-whatsapp:hover {
      background-color: var(--primary-hover);
    }

    .btn-copy {
      background-color: #eff6ff;
      color: var(--secondary);
      border: 1px solid #bfdbfe;
    }

    .btn-copy:hover {
      background-color: #dbeafe;
    }

    .toast {
      display: none;
      margin-top: 12px;
      padding: 10px 12px;
      border-radius: 8px;
      background-color: #ecfdf5;
      color: #065f46;
      border: 1px solid #a7f3d0;
      font-size: 13px;
      text-align: center;
    }

    .preview-box {
      margin-top: 18px;
      padding: 12px;
      background: #f9fafb;
      border: 1px dashed #d1d5db;
      border-radius: 8px;
      font-size: 13px;
      color: #4b5563;
      white-space: pre-wrap;
      line-height: 1.5;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="header">
    <h1>KLA Daily tracking</h1>
    <p>填写完成后可直接发送至 WhatsApp 或一键复制发到工作群</p>
  </div>

  <form id="trackingForm" onsubmit="return false;">
    <!-- Date -->
    <div class="form-group">
      <label class="field-title" for="trackDate"><span class="req">*</span>Date (日期)</label>
      <input type="date" id="trackDate" required />
    </div>

    <!-- Team -->
    <div class="form-group">
      <label class="field-title" for="team"><span class="req">*</span>Team</label>
      <select id="team" required>
        <option value="" disabled selected>请选择 Team...</option>
        <option value="Assembly">Assembly</option>
        <option value="Test">Test</option>
      </select>
    </div>

    <!-- Name -->
    <div class="form-group">
      <label class="field-title" for="userName"><span class="req">*</span>Name</label>
      <input type="text" id="userName" placeholder="请输入您的姓名" required />
    </div>

    <!-- Product Model -->
    <div class="form-group">
      <label class="field-title"><span class="req">*</span>Product Model (可多选)</label>
      <div class="checkbox-grid" id="modelGroup">
        <label class="checkbox-item"><input type="checkbox" name="model" value="P-series" /> P-series</label>
        <label class="checkbox-item"><input type="checkbox" name="model" value="P170" /> P170</label>
        <label class="checkbox-item"><input type="checkbox" name="model" value="D500/D600" /> D500/D600</label>
        <label class="checkbox-item"><input type="checkbox" name="model" value="HRP" /> HRP</label>
        <label class="checkbox-item"><input type="checkbox" name="model" value="Z-20" /> Z-20</label>
        <label class="checkbox-item"><input type="checkbox" name="model" value="Z-300/Z-388" /> Z-300/Z-388</label>
      </div>
    </div>

    <!-- UTID -->
    <div class="form-group">
      <label class="field-title" for="utid"><span class="req">*</span>UTID</label>
      <input type="text" id="utid" placeholder="例如: 1024" required />
    </div>

    <!-- Progress % -->
    <div class="form-group">
      <label class="field-title" for="progress"><span class="req">*</span>Progress %</label>
      <input type="number" id="progress" min="0" max="100" placeholder="0 - 100" required />
    </div>

    <!-- 实时预览生成的文本 -->
    <div class="preview-box" id="livePreview">填写上方内容后，此处将实时预览生成结果...</div>

    <div class="btn-group">
      <button type="button" class="btn-whatsapp" onclick="sendToWhatsApp()">
        发送至 WhatsApp (+60 16-4146-623)
      </button>
      <button type="button" class="btn-copy" onclick="copyReport()">
        一键复制内容（方便发到群里）
      </button>
    </div>

    <div class="toast" id="toastMsg">✅ 已复制到剪贴板！请直接去 WhatsApp 群粘贴发送。</div>
  </form>
</div>

<script>
  // 目标 WhatsApp 号码（不含加号和空格）
  const TARGET_PHONE = "60164146623";

  // 默认自动填入今天日期
  const dateInput = document.getElementById("trackDate");
  const today = new Date();
  const yyyy = today.getFullYear();
  const mm = String(today.getMonth() + 1).padStart(2, "0");
  const dd = String(today.getDate()).padStart(2, "0");
  dateInput.value = `${yyyy}-${mm}-${dd}`;

  // 获取并校验表单数据
  function getFormData(validate = true) {
    const date = document.getElementById("trackDate").value;
    const team = document.getElementById("team").value;
    const name = document.getElementById("userName").value.trim();
    const utid = document.getElementById("utid").value.trim();
    const progress = document.getElementById("progress").value.trim();

    const checkedModels = Array.from(document.querySelectorAll('input[name="model"]:checked'))
      .map(cb => cb.value);

    if (validate) {
      if (!date || !team || !name || checkedModels.length === 0 || !utid || progress === "") {
        alert("请完整填写所有带 * 号的必填项（包括至少勾选一个 Product Model）！");
        return null;
      }
      if (Number(progress) < 0 || Number(progress) > 100) {
        alert("Progress % 请输入 0 到 100 之间的数字！");
        return null;
      }
    }

    return {
      date: date || "-",
      team: team || "-",
      name: name || "-",
      models: checkedModels.length > 0 ? checkedModels.join(", ") : "-",
      utid: utid || "-",
      progress: progress !== "" ? `${progress}%` : "-"
    };
  }

  // 格式化输出的打卡文本
  function formatMessage(data) {
    return `*KLA Daily tracking*\n` +
           `📅 Date: ${data.date}\n` +
           `👥 Team: ${data.team}\n` +
           `👤 Name: ${data.name}\n` +
           `📦 Product Model: ${data.models}\n` +
           `🔢 UTID: ${data.utid}\n` +
           `📊 Progress: ${data.progress}`;
  }

  // 实时更新底部预览框
  function updatePreview() {
    const data = getFormData(false);
    document.getElementById("livePreview").textContent = formatMessage(data);
  }

  // 监听所有输入变化
  document.getElementById("trackingForm").addEventListener("input", updatePreview);
  document.getElementById("trackingForm").addEventListener("change", updatePreview);
  updatePreview();

  // 1. 直接跳转 WhatsApp 发送
  function sendToWhatsApp() {
    const data = getFormData(true);
    if (!data) return;

    const text = encodeURIComponent(formatMessage(data));
    const waUrl = `https://wa.me/${TARGET_PHONE}?text=${text}`;
    window.open(waUrl, "_blank");
  }

  // 2. 一键复制到剪贴板
  async function copyReport() {
    const data = getFormData(true);
    if (!data) return;

    const plainText = formatMessage(data);
    try {
      await navigator.clipboard.writeText(plainText);
      showToast();
    } catch (err) {
      // 兼容部分手机内置浏览器不支持 clipboard API 的情况
      const textarea = document.createElement("textarea");
      textarea.value = plainText;
      document.body.appendChild(textarea);
      textarea.select();
      document.execCommand("copy");
      document.body.removeChild(textarea);
      showToast();
    }
  }

  function showToast() {
    const toast = document.getElementById("toastMsg");
    toast.style.display = "block";
    setTimeout(() => {
      toast.style.display = "none";
    }, 4000);
  }
</script>

</body>
</html>
