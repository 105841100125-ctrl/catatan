/* ============================================
   CSS Variables & Reset
   ============================================ */
:root {
    --primary: #4f46e5;
    --primary-hover: #4338ca;
    --primary-light: #eef2ff;
    --danger: #ef4444;
    --danger-hover: #dc2626;
    --danger-light: #fef2f2;
    --success: #10b981;
    --success-light: #ecfdf5;
    --warning: #f59e0b;
    --bg: #f1f5f9;
    --surface: #ffffff;
    --surface-alt: #f8fafc;
    --text: #1e293b;
    --text-secondary: #64748b;
    --text-muted: #94a3b8;
    --border: #e2e8f0;
    --border-focus: #a5b4fc;
    --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05);
    --shadow: 0 1px 3px rgba(0, 0, 0, 0.1), 0 1px 2px rgba(0, 0, 0, 0.06);
    --shadow-md: 0 4px 6px rgba(0, 0, 0, 0.07), 0 2px 4px rgba(0, 0, 0, 0.06);
    --shadow-lg: 0 10px 25px rgba(0, 0, 0, 0.1), 0 4px 10px rgba(0, 0, 0, 0.05);
    --radius-sm: 8px;
    --radius: 12px;
    --radius-lg: 16px;
    --radius-xl: 20px;
    --transition: 0.2s ease;
    --transition-slow: 0.35s ease;
    --font-sans: 'Inter', 'Segoe UI', system-ui, -apple-system, sans-serif;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: var(--font-sans);
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
    min-height: 100vh;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

/* ============================================
   Container
   ============================================ */
.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 0 20px;
}

/* ============================================
   Header
   ============================================ */
.header {
    background: var(--surface);
    border-bottom: 1px solid var(--border);
    padding: 20px 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: var(--shadow-sm);
}

.header-content {
    display: flex;
    align-items: center;
    gap: 16px;
    flex-wrap: wrap;
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    color: var(--primary);
}

.logo i {
    font-size: 28px;
}

.logo h1 {
    font-size: 1.5rem;
    font-weight: 700;
    letter-spacing: -0.02em;
}

.header-subtitle {
    color: var(--text-secondary);
    font-size: 0.875rem;
    margin-left: 4px;
}

/* ============================================
   Main Content
   ============================================ */
.main {
    padding: 28px 20px 60px;
}

/* ============================================
   Form Card
   ============================================ */
.note-form-section {
    margin-bottom: 24px;
}

.form-card {
    background: var(--surface);
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-md);
    overflow: hidden;
    transition: box-shadow var(--transition);
}

.form-card:hover {
    box-shadow: var(--shadow-lg);
}

.form-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 16px 20px;
    background: var(--surface-alt);
    border-bottom: 1px solid var(--border);
    cursor: pointer;
    user-select: none;
}

.form-header h2 {
    font-size: 1.1rem;
    font-weight: 600;
    display: flex;
    align-items: center;
    gap: 8px;
    color: var(--text);
}

.form-header h2 i {
    color: var(--primary);
    font-size: 1.2rem;
}

.btn-collapse {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 50%;
    width: 36px;
    height: 36px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--text-secondary);
    transition: all var(--transition);
    font-size: 0.9rem;
}

.btn-collapse:hover {
    background: var(--primary-light);
    color: var(--primary);
    border-color: var(--border-focus);
}

.btn-collapse.collapsed i {
    transform: rotate(180deg);
}

.btn-collapse i {
    transition: transform var(--transition-slow);
}

.form-body {
    padding: 20px;
    transition: max-height var(--transition-slow), opacity var(--transition-slow), padding var(--transition-slow);
    max-height: 800px;
    opacity: 1;
    overflow: hidden;
}

.form-body.collapsed {
    max-height: 0;
    opacity: 0;
    padding: 0 20px;
}

.input-group {
    margin-bottom: 16px;
    position: relative;
}

.input-group label {
    display: block;
    font-weight: 600;
    font-size: 0.9rem;
    margin-bottom: 6px;
    color: var(--text);
}

.input-group label i {
    color: var(--primary);
    margin-right: 4px;
    font-size: 0.85rem;
}

.input-group input[type="text"],
.input-group textarea {
    width: 100%;
    padding: 12px 16px;
    border: 2px solid var(--border);
    border-radius: var(--radius);
    font-family: var(--font-sans);
    font-size: 0.95rem;
    color: var(--text);
    background: var(--surface);
    transition: all var(--transition);
    resize: vertical;
    line-height: 1.5;
}

.input-group input[type="text"]:focus,
.input-group textarea:focus {
    outline: none;
    border-color: var(--border-focus);
    box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.1);
}

.input-group input[type="text"]::placeholder,
.input-group textarea::placeholder {
    color: var(--text-muted);
}

.char-count {
    position: absolute;
    bottom: 10px;
    right: 14px;
    font-size: 0.75rem;
    color: var(--text-muted);
    background: var(--surface-alt);
    padding: 2px 8px;
    border-radius: 4px;
    pointer-events: none;
}

.input-group textarea ~ .char-count {
    bottom: 14px;
}

/* Color Picker */
.color-picker-group label {
    margin-bottom: 10px;
}

.color-options {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

.color-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 3px solid transparent;
    cursor: pointer;
    transition: all var(--transition);
    box-shadow: var(--shadow-sm);
    position: relative;
}

.color-btn:hover {
    transform: scale(1.15);
    box-shadow: var(--shadow-md);
}

.color-btn.active {
    border-color: var(--primary);
    box-shadow: 0 0 0 4px rgba(79, 70, 229, 0.2);
}

.color-btn.active::after {
    content: '✓';
    position: absolute;
    inset: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 0.8rem;
    color: var(--text);
}

/* Form Actions */
.form-actions {
    display: flex;
    gap: 10px;
    margin-top: 8px;
}

.form-message {
    margin-top: 10px;
    padding: 10px 14px;
    border-radius: var(--radius-sm);
    font-size: 0.875rem;
    font-weight: 500;
}

.form-message.error {
    background: var(--danger-light);
    color: var(--danger);
    border: 1px solid #fecaca;
}

.form-message.success {
    background: var(--success-light);
    color: var(--success);
    border: 1px solid #a7f3d0;
}

/* ============================================
   Buttons
   ============================================ */
.btn {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 10px 20px;
    border-radius: var(--radius);
    font-family: var(--font-sans);
    font-size: 0.9rem;
    font-weight: 600;
    cursor: pointer;
    border: 2px solid transparent;
    transition: all var(--transition);
    white-space: nowrap;
    text-decoration: none;
}

.btn:active {
    transform: scale(0.97);
}

.btn-primary {
    background: var(--primary);
    color: #fff;
    border-color: var(--primary);
}

.btn-primary:hover {
    background: var(--primary-hover);
    border-color: var(--primary-hover);
    box-shadow: var(--shadow-md);
}

.btn-outline {
    background: var(--surface);
    color: var(--text);
    border-color: var(--border);
}

.btn-outline:hover {
    background: var(--surface-alt);
    border-color: var(--text-muted);
}

.btn-danger {
    background: var(--danger);
    color: #fff;
    border-color: var(--danger);
}

.btn-danger:hover {
    background: var(--danger-hover);
    border-color: var(--danger-hover);
}

.btn-danger-outline {
    background: var(--surface);
    color: var(--danger);
    border-color: #fecaca;
}

.btn-danger-outline:hover {
    background: var(--danger-light);
    border-color: var(--danger);
}

.btn-sm {
    padding: 7px 14px;
    font-size: 0.8rem;
    border-radius: var(--radius-sm);
}

/* ============================================
   Toolbar & Search
   ============================================ */
.toolbar-section {
    margin-bottom: 20px;
}

.toolbar {
    display: flex;
    align-items: center;
    gap: 12px;
    flex-wrap: wrap;
    justify-content: space-between;
}

.search-box {
    position: relative;
    flex: 1;
    min-width: 220px;
    max-width: 450px;
}

.search-box i {
    position: absolute;
    left: 14px;
    top: 50%;
    transform: translateY(-50%);
    color: var(--text-muted);
    font-size: 0.9rem;
    pointer-events: none;
}

.search-box input {
    width: 100%;
    padding: 10px 40px 10px 40px;
    border: 2px solid var(--border);
    border-radius: var(--radius-xl);
    font-family: var(--font-sans);
    font-size: 0.9rem;
    background: var(--surface);
    color: var(--text);
    transition: all var(--transition);
}

.search-box input:focus {
    outline: none;
    border-color: var(--border-focus);
    box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.08);
}

.search-box input::placeholder {
    color: var(--text-muted);
}

.btn-clear-search {
    position: absolute;
    right: 8px;
    top: 50%;
    transform: translateY(-50%);
    background: var(--bg);
    border: none;
    border-radius: 50%;
    width: 28px;
    height: 28px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--text-secondary);
    transition: all var(--transition);
    font-size: 0.75rem;
}

.btn-clear-search:hover {
    background: #e2e8f0;
    color: var(--text);
}

.toolbar-info {
    display: flex;
    align-items: center;
    gap: 10px;
}

.note-count {
    font-size: 0.85rem;
    color: var(--text-secondary);
    font-weight: 500;
    background: var(--surface);
    padding: 6px 14px;
    border-radius: var(--radius-xl);
    border: 1px solid var(--border);
}

/* ============================================
   Notes Grid
   ============================================ */
.notes-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 16px;
}

/* Note Card */
.note-card {
    background: var(--surface);
    border-radius: var(--radius-lg);
    padding: 20px;
    box-shadow: var(--shadow);
    border: 1px solid var(--border);
    transition: all var(--transition);
    display: flex;
    flex-direction: column;
    gap: 10px;
    position: relative;
    animation: fadeInUp 0.4s ease forwards;
    opacity: 0;
    cursor: default;
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(16px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.note-card:hover {
    box-shadow: var(--shadow-lg);
    transform: translateY(-2px);
    border-color: #cbd5e1;
}

.note-card-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 8px;
}

.note-card-title {
    font-weight: 700;
    font-size: 1rem;
    color: var(--text);
    line-height: 1.3;
    word-break: break-word;
    flex: 1;
}

.note-card-actions {
    display: flex;
    gap: 4px;
    opacity: 0;
    transition: opacity var(--transition);
    flex-shrink: 0;
}

.note-card:hover .note-card-actions {
    opacity: 1;
}

.note-card-actions button {
    width: 32px;
    height: 32px;
    border-radius: 50%;
    border: 1px solid transparent;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.8rem;
    transition: all var(--transition);
    background: transparent;
    color: var(--text-muted);
}

.note-card-actions .btn-edit:hover {
    background: var(--primary-light);
    color: var(--primary);
    border-color: var(--border-focus);
}

.note-card-actions .btn-delete:hover {
    background: var(--danger-light);
    color: var(--danger);
    border-color: #fecaca;
}

.note-card-content {
    font-size: 0.9rem;
    color: var(--text-secondary);
    line-height: 1.5;
    word-break: break-word;
    display: -webkit-box;
    -webkit-box-orient: vertical;
    overflow: hidden;
    flex: 1;
}

.note-card-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 0.75rem;
    color: var(--text-muted);
    padding-top: 6px;
    border-top: 1px solid var(--border);
}

.note-card-date {
    display: flex;
    align-items: center;
    gap: 4px;
}

/* ============================================
   Empty State
   ============================================ */
.empty-state {
    text-align: center;
    padding: 60px 20px;
    color: var(--text-secondary);
}

.empty-state-icon {
    font-size: 4rem;
    color: var(--text-muted);
    margin-bottom: 16px;
    opacity: 0.6;
}

.empty-state h3 {
    font-size: 1.3rem;
    font-weight: 600;
    margin-bottom: 6px;
    color: var(--text);
}

.empty-state p {
    font-size: 0.9rem;
    color: var(--text-muted);
}

/* ============================================
   Modal
   ============================================ */
.modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(15, 23, 42, 0.6);
    backdrop-filter: blur(4px);
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: fadeIn 0.2s ease;
    padding: 20px;
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

.modal {
    background: var(--surface);
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-lg);
    max-width: 420px;
    width: 100%;
    overflow: hidden;
    animation: scaleIn 0.25s ease;
}

@keyframes scaleIn {
    from {
        opacity: 0;
        transform: scale(0.9);
    }
    to {
        opacity: 1;
        transform: scale(1);
    }
}

.modal-header {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 20px 24px 0;
    color: var(--danger);
}

.modal-header i {
    font-size: 1.5rem;
}

.modal-header h3 {
    font-size: 1.1rem;
    font-weight: 700;
    color: var(--text);
}

.modal-body {
    padding: 12px 24px 20px;
}

.modal-body p {
    font-size: 0.95rem;
    color: var(--text-secondary);
}

.modal-warning {
    font-size: 0.8rem !important;
    color: var(--danger) !important;
    margin-top: 4px;
    font-weight: 500;
}

.modal-footer {
    display: flex;
    justify-content: flex-end;
    gap: 10px;
    padding: 16px 24px;
    background: var(--surface-alt);
    border-top: 1px solid var(--border);
}

/* ============================================
   Toast Notification
   ============================================ */
.toast-container {
    position: fixed;
    bottom: 24px;
    right: 24px;
    z-index: 2000;
    display: flex;
    flex-direction: column;
    gap: 8px;
    pointer-events: none;
}

.toast {
    background: var(--surface);
    color: var(--text);
    padding: 14px 20px;
    border-radius: var(--radius);
    box-shadow: var(--shadow-lg);
    font-size: 0.9rem;
    font-weight: 500;
    display: flex;
    align-items: center;
    gap: 10px;
    animation: toastIn 0.35s ease, toastOut 0.3s ease 2.5s forwards;
    pointer-events: auto;
    max-width: 380px;
    border-left: 4px solid var(--primary);
}

.toast.success {
    border-left-color: var(--success);
}

.toast.error {
    border-left-color: var(--danger);
}

.toast i {
    font-size: 1.1rem;
    flex-shrink: 0;
}

.toast.success i {
    color: var(--success);
}

.toast.error i {
    color: var(--danger);
}

@keyframes toastIn {
    from {
        opacity: 0;
        transform: translateX(100px);
    }
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

@keyframes toastOut {
    from {
        opacity: 1;
        transform: translateX(0);
    }
    to {
        opacity: 0;
        transform: translateX(100px);
    }
}

/* ============================================
   Utility
   ============================================ */
.hidden {
    display: none !important;
}

/* ============================================
   Responsive
   ============================================ */
@media (max-width: 768px) {
    .header-content {
        flex-direction: column;
        align-items: flex-start;
        gap: 4px;
    }

    .header-subtitle {
        margin-left: 0;
    }

    .toolbar {
        flex-direction: column;
        align-items: stretch;
    }

    .search-box {
        max-width: 100%;
    }

    .toolbar-info {
        justify-content: space-between;
    }

    .notes-grid {
        grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
        gap: 12px;
    }

    .note-card-actions {
        opacity: 1;
    }

    .form-actions {
        flex-direction: column;
    }

    .form-actions .btn {
        width: 100%;
        justify-content: center;
    }

    .toast-container {
        bottom: 16px;
        right: 16px;
        left: 16px;
    }

    .toast {
        max-width: 100%;
    }
}

@media (max-width: 400px) {
    .notes-grid {
        grid-template-columns: 1fr;
    }

    .header {
        padding: 14px 0;
    }

    .logo h1 {
        font-size: 1.25rem;
    }

    .main {
        padding: 16px 12px 40px;
    }

    .form-body {
        padding: 14px;
    }
}