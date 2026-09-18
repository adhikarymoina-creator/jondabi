# Roadmap

- [x] City corporations + municipalities in bd-locations.json
- [x] Ward model (9 per union/municipality/city corporation) in locations.ts
- [x] Ward dropdown in LocationFilter (grouped upazila/city-corp and union/পৌরসভা options)
- [x] Store ward on submitted demands (ward_id column + area label)
- [x] Home page filtering by ward
- [x] Verified: exactly 9 wards (ওয়ার্ড ০১–০৯), scoped per union, no leaks
- [x] Verified: ward disabled until union/city corporation selected, resets on upstream change
- [x] Verified: ward -> union -> upazila mapping correct across two unions
- [x] Verified: city corporations and municipalities selectable under their districts
- [x] Rebuilt demands database after it was found empty
- [x] Fix storage bucket access rules (owner-only upload/read)
- [x] Hide submitter identity from public demand reads
- [x] Restrict SECURITY DEFINER function execution
- [x] Test both signed-out and signed-in access paths
- [x] Re-run security scan and report status per issue
- [x] Automated regression tests for the three security areas
- [x] Prove anon/non-owner cannot upload or read attachments; document policy SQL
