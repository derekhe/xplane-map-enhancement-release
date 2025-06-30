# KRDM Airport Orthophoto Fix Checklist

**Airport**: KRDM - Redmond-Roberts Field, Oregon  
**Issue**: Orthophotos not downloading properly (shows 77 photos but only default textures in X-Plane)  
**Coordinates**: 44.253025, -121.1608351

## Step-by-Step Fix Process

### ✅ Prerequisites Check
- [ ] X-Plane Map Enhancement version 3.0.12.0 or newer
- [ ] Base Package version 2.0.1 or newer  
- [ ] Stable internet connection
- [ ] X-Plane is closed during this process

### 🔧 Step 1: Remove Third-Party Content (MOST IMPORTANT)
**This is the #1 cause of KRDM orthophoto issues**

- [ ] Check X-Plane Custom Scenery folder for KRDM airports
- [ ] Look for files containing "KRDM", "Redmond", or "Roberts" 
- [ ] Temporarily move any KRDM-related airports out of Custom Scenery
- [ ] Common third-party KRDM packages to check for:
  - [ ] Any freeware KRDM scenery
  - [ ] Payware KRDM airports
  - [ ] Scenery gateway versions

### 🧹 Step 2: Clear KRDM Data
- [ ] Open X-Plane Map Enhancement
- [ ] Navigate to orthophoto cache location
- [ ] Delete any existing KRDM orthophoto files/folders
- [ ] Clear application cache if available
- [ ] Restart X-Plane Map Enhancement

### 📥 Step 3: Fresh Download
- [ ] In X-Plane Map Enhancement, navigate to KRDM coordinates
- [ ] Verify location: 44.253025, -121.1608351
- [ ] Clear any existing downloads for this area
- [ ] Start fresh orthophoto download
- [ ] Wait for completion (should show more than 77 photos)
- [ ] Note the actual number of photos downloaded: ________

### 🧪 Step 4: Test in X-Plane
- [ ] Start X-Plane
- [ ] Load aircraft at KRDM
- [ ] Check if satellite imagery is visible
- [ ] Test different camera angles and zoom levels
- [ ] Take screenshots for comparison

### 📋 Results Check
**After completing all steps:**

- [ ] ✅ Issue resolved - satellite imagery now visible
- [ ] ⚠️ Partial improvement - some areas have imagery
- [ ] ❌ No change - still only default textures

### 🔄 If Issue Persists

Try these additional steps:

#### Version Troubleshooting
- [ ] Try Base Package version 2.0.0 instead of 2.0.1
- [ ] If available, test with X-Plane Map Enhancement 3.0.15.0

#### Network Troubleshooting  
- [ ] Try downloading during different hours
- [ ] Check firewall/antivirus isn't blocking the application
- [ ] Test with VPN if available

#### Clean Installation Test
- [ ] Create backup of current settings
- [ ] Clean install of X-Plane Map Enhancement
- [ ] Test KRDM without any other modifications

### 📝 Documentation

**What worked for you?**
- Step that resolved the issue: ________________
- Final photo count downloaded: ________________
- Software versions used: ________________
- Notes: ________________

### 🆘 Still Not Working?

If you've completed all steps and the issue persists:

1. **Document your results** using the information above
2. **Take screenshots** of the issue and software settings
3. **Report to GitHub Issue #185** with your findings
4. **Include your Device ID**: YDR04PCDSZJFQPQCQW3SS6EVHZ5TXNSNHB52B3JMV93TS4503MGG (if this is your issue)

---

## Success Stories

**Share your fix!** If this checklist resolves your KRDM issue, please comment on [GitHub Issue #185](https://github.com/derekhe/xplane-map-enhancement-release/issues/185) to help others.

---

*Last updated: 2025-06-30*