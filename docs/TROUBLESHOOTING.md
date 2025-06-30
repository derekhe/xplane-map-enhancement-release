# X-Plane Map Enhancement Troubleshooting Guide

This guide helps resolve common issues with orthophoto downloading and display in X-Plane Map Enhancement.

## Orthophoto Issues

### Symptoms
- Software indicates photos are downloading but only default textures appear in X-Plane
- Limited number of photos downloaded (e.g., "loaded only 77 photos")
- Black squares or missing textures in specific areas
- Terrain covered in water when it shouldn't be

### Common Causes and Solutions

#### 1. Third-Party Airport Conflicts
**Problem**: Custom or third-party airports can interfere with orthophoto display.

**Solution**:
1. Check if you have any custom airports installed for the affected area
2. Temporarily disable or remove third-party airports
3. Test orthophoto downloading again
4. If this resolves the issue, the third-party airport may need to be updated or configured differently

#### 2. Coverage Limitations
**Problem**: Some geographical areas may have limited or no orthophoto coverage.

**Indicators**:
- Rural or remote locations
- Areas with restricted airspace
- Regions with limited satellite imagery availability

**Solution**:
- Check with the community or documentation for known coverage limitations
- Consider using alternative map sources if available
- Report the issue if you believe the area should be covered

#### 3. Base Package Version Compatibility
**Problem**: Mismatched versions between X-Plane Map Enhancement and Base Package.

**Solution**:
1. Verify you're using compatible versions:
   - X-Plane Map Enhancement: Latest version (3.0.15.0+)
   - Base Package: Latest version (2.0.1+)
2. Download and install the latest Base Package
3. Restart the application and try again

#### 4. Network and Connection Issues
**Problem**: Poor connection to orthophoto servers or timeouts.

**Solution**:
1. Check your internet connection stability
2. Try downloading during off-peak hours
3. Restart the application
4. Check firewall settings that might block the application

#### 5. Cache and Data Corruption
**Problem**: Corrupted cache or incomplete downloads.

**Solution**:
1. Clear the application cache
2. Delete any partially downloaded orthophoto data for the affected area
3. Restart the application
4. Re-download the orthophotos for the area

### Airport-Specific Issues

#### KRDM (Redmond-Roberts Field, Oregon)
**Location**: Latitude 44.253025, Longitude -121.1608351
**Known Issue**: Orthophotos not downloading properly despite showing 77 photos loaded

**Troubleshooting Steps**:
1. **Check for third-party airports**: Remove any custom KRDM airport packages
2. **Verify coordinates**: Ensure you're downloading for the correct location
3. **Coverage verification**: This area should have orthophoto coverage
4. **Clear local data**: 
   - Delete any existing KRDM orthophoto cache
   - Restart application
   - Re-download for the area
5. **Version check**: Ensure you're using:
   - X-Plane Map Enhancement 3.0.12.0 or newer
   - Base Package 2.0.1 or newer

### Reporting Issues

When reporting orthophoto issues, please include:

1. **Location Information**:
   - Airport ICAO code (if applicable)
   - Latitude and Longitude coordinates
   - General area description

2. **Version Information**:
   - X-Plane Map Enhancement version
   - Base Package version
   - Device ID from license page

3. **Symptoms**:
   - What you expect to see vs. what actually appears
   - Number of photos reportedly downloaded
   - Screenshots or videos of the issue

4. **Environment**:
   - Are you using custom airports, mesh, or orthophotos?
   - Any third-party scenery packages installed?
   - X-Plane version

5. **Troubleshooting Attempted**:
   - What steps you've already tried
   - Whether the issue is consistent or intermittent

### Getting Help

- Check the [User Manual](https://github.com/derekhe/xplane-map-enhancement-release/wiki/Manual-EN)
- Search existing [GitHub Issues](https://github.com/derekhe/xplane-map-enhancement-release/issues)
- Report new issues using the bug report template
- Community forums and Discord channels (check project documentation for links)