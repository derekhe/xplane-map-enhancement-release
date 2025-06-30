# Quick Fix Guide for Orthophoto Issues

**Having problems with orthophotos not showing in X-Plane? Try these steps in order:**

## 🔧 Quick Fixes (Try These First)

### 1. Remove Third-Party Airports
- Check if you have custom airports installed for the area
- Temporarily disable/remove them
- Test orthophoto downloading again

### 2. Version Check
- **X-Plane Map Enhancement**: Use latest version (3.0.15.0+)
- **Base Package**: Use latest version (2.0.1+)
- If issues persist, try Base Package 2.0.0

### 3. Clear Cache & Restart
- Clear orthophoto cache for the problem area
- Restart X-Plane Map Enhancement
- Re-download orthophotos

### 4. Check Network Connection
- Ensure stable internet connection
- Try downloading during off-peak hours
- Check firewall isn't blocking the application

## 🏟️ Airport-Specific Quick Fixes

### KRDM (Redmond, Oregon)
```
Problem: Shows "77 photos loaded" but only default textures in X-Plane
Quick Fix: Remove any custom KRDM airports → Clear cache → Restart → Re-download
```
📋 **[Complete KRDM Fix Checklist](KRDM_FIX_CHECKLIST.md)** - Step-by-step guide

### KBHM (Birmingham, Alabama)  
```
Problem: Area covered in water with Base Package 2.0.1
Quick Fix: Downgrade to Base Package 2.0.0
```

### YSSY (Sydney, Australia)
```
Problem: Runways have humps, very hilly terrain
Status: Known issue, elevation data problem
```

## 🚨 When to Report a Bug

Report if you've tried all quick fixes and:
- ✅ Verified versions are compatible
- ✅ Tried without third-party airports
- ✅ Cleared cache and restarted
- ✅ Tested network connection

## 📝 What to Include in Bug Reports

**Copy this checklist when reporting:**

```
- [ ] Airport ICAO: ____
- [ ] Coordinates: ____
- [ ] X-Plane Map Enhancement Version: ____
- [ ] Base Package Version: ____
- [ ] Device ID: ____
- [ ] Custom airports removed: Yes/No
- [ ] Cache cleared: Yes/No
- [ ] Screenshots attached: Yes/No
- [ ] Issue reproducible: Yes/No
```

## 🔗 More Help

- 📖 [Full Troubleshooting Guide](TROUBLESHOOTING.md)
- 🐛 [Known Issues List](KNOWN_ISSUES.md)
- 📚 [User Manual](https://github.com/derekhe/xplane-map-enhancement-release/wiki/Manual-EN)
- 🎫 [Report New Issue](https://github.com/derekhe/xplane-map-enhancement-release/issues/new?template=bug_report.md)