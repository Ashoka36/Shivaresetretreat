# 🌐 DNS Configuration for shivasresetretreat.dpdns.org

## ⚠️ Important: DNS Configuration Required

Your custom domain `shivasresetretreat.dpdns.org` needs DNS records configured to point to GitHub Pages.

---

## 🔧 DNS Records to Add

Add these DNS records to your DPDNS account:

### A Records (Recommended - Add All 4)
```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

---

## 📋 Steps to Configure DNS at DPDNS

### Step 1: Log in to DPDNS
1. Go to your DPDNS account dashboard
2. Find domain: `shivasresetretreat.dpdns.org`
3. Click "Manage DNS" or "DNS Settings"

### Step 2: Add A Records
1. Click "Add Record" or "New Record"
2. Select Type: **A**
3. Name: **@** (or leave blank)
4. Value: **185.199.108.153** (first record)
5. Click Save
6. Repeat for the other 3 IP addresses

### Step 3: Wait for Propagation
- DNS changes take 5 minutes to 48 hours
- Check status: https://www.whatsmydns.net/

### Step 4: Enable GitHub Pages
1. Go to: https://github.com/Ashoka36/Shiva-s-Reset-Retreat/settings
2. Scroll to **Pages**
3. Under "Custom domain", enter: `shivasresetretreat.dpdns.org`
4. Click **Save**
5. Check "Enforce HTTPS" (after DNS works)

---

## ✅ Current Status

- ✅ CNAME file created with your domain
- ✅ Repository ready for custom domain
- ⏳ Waiting for DNS configuration at DPDNS

---

## 🔍 Verify DNS Setup

```bash
# Check DNS resolution
nslookup shivasresetretreat.dpdns.org

# Should show GitHub's IP addresses:
# 185.199.108.153
# 185.199.109.153
# 185.199.110.153
# 185.199.111.153
```

---

## 🌐 URLs After Setup

| URL | Status |
|-----|--------|
| `https://shivasresetretreat.dpdns.org` | ✅ Custom domain (after DNS) |
| `https://ashoka36.github.io/Shiva-s-Reset-Retreat/` | ✅ Fallback (always works) |

---

## ⏱️ Timeline

1. **Now**: Add 4 A records to DPDNS
2. **5 min - 48 hours**: DNS propagation
3. **After propagation**: Custom domain works
4. **Fallback**: GitHub Pages URL always works

---

**Next: Add the 4 A records to your DPDNS account!**
