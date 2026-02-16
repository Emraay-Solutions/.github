---
name: Deployment Task
about: Standard deployment checklist for any application
title: "[DEPLOY] "
labels: deployment
assignees: ''
---

## 🚀 Deployment Task

### 📌 App Information
- **App:** 
- **Repo:** 
- **VM:** 
- **Zone:** 
- **App Directory on VM:** 
- **Compose File:** 
- **Workflow:** 

---

## ✅ Pre-Deployment Checklist
- [ ] Confirm latest commit builds successfully
- [ ] Confirm secrets are available in GitHub Actions
- [ ] Confirm VM is reachable
- [ ] Confirm compose file exists
- [ ] Confirm disk space is sufficient

---

## 🔧 Deployment Steps
- [ ] SSH into VM
- [ ] Navigate to app directory
- [ ] Pull latest code
- [ ] Stop existing container
- [ ] Build new image
- [ ] Start container
- [ ] Prune unused images

---

## 🔍 Post-Deployment Validation
- [ ] App loads successfully
- [ ] No errors in container logs
- [ ] Health checks pass
- [ ] Notify team deployment is complete

---

## 📝 Notes
(Add any relevant details here.)
