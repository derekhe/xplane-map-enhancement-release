# Known Orthophoto Issues by Airport

This file tracks airports and locations with known orthophoto downloading or display issues.

## Problematic Airports

### KRDM - Redmond-Roberts Field, Oregon, USA
- **Coordinates**: 44.253025, -121.1608351
- **Issue**: Orthophotos not downloading properly
- **Symptoms**: Software shows photos downloading (77 photos loaded) but only default textures visible in X-Plane
- **Status**: Under investigation
- **Workarounds**:
  1. Check for and remove any third-party KRDM airport packages
  2. Clear orthophoto cache for the area
  3. Ensure using X-Plane Map Enhancement 3.0.12.0+ and Base Package 2.0.1+
- **Last Updated**: 2025-06-30
- **Reporter**: 770fs (GitHub issue #185)

### Other Reported Issues

#### YSSY - Sydney Kingsford Smith Airport, Australia
- **Issue**: Terrain extremely hilly, runways have humps
- **Status**: Open (GitHub issue #195)
- **Note**: Elevation data may be incorrect

#### LGAV - Athens International Airport, Greece  
- **Issue**: Heavy bumps on apron
- **Status**: Open (GitHub issue #192)
- **Note**: Elevation/terrain mesh issues

#### KBHM - Birmingham-Shuttlesworth International Airport, Alabama, USA
- **Issue**: Area covered in water with Base Package 2.0.1
- **Status**: Open (GitHub issue #194)
- **Workaround**: Revert to Base Package 2.0.0

## Coverage Limitations

### Northern Russia
- **Issue**: Missing orthophoto coverage, black squares appearing
- **Status**: Open (GitHub issue #197)
- **Note**: May be related to data source limitations in remote areas

## Version-Specific Issues

### Base Package 2.0.1
- Some users experiencing water coverage issues in areas that should be land
- Consider reverting to Base Package 2.0.0 if experiencing these issues

### X-Plane Map Enhancement 3.0.15.0
- Some users reporting "Access remote image server error" with Hybrid Map (Pro)
- Workaround: Downgrade to version 3.0.12.0 if needed

## How to Report New Issues

When you encounter orthophoto issues:

1. Check this list to see if your airport/area is already known
2. If not listed, create a new GitHub issue with:
   - Airport ICAO code and coordinates
   - Detailed description of the problem
   - Screenshots/videos
   - Your version information
   - Steps you've tried to resolve it

## Contributing

If you find a workaround for any of these issues, please:
1. Comment on the related GitHub issue
2. Submit a PR to update this documentation

---

*This file is maintained by the community. Last updated: 2025-06-30*