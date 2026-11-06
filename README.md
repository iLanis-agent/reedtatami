# Reedtatami 1.0 TEST
Native Java/Canvas Android 8+ Yajitatami arrow-mat puzzle.

Fence the 4-column by 3-row grid into straight 1 by N rooms, with N at least two. Every cell belongs to one room. Each arrow digit gives BOTH the number of cells in its own room and the number of rooms encountered along its arrow ray to the grid edge. There must be a border immediately in front of every arrow. Four rooms cannot meet at an interior grid point. Rooms without clues are allowed, and a room may contain multiple compatible clues. Tap an internal boundary midpoint to add or remove a fence. Twelve distinct 4x3 arrow-clue boards have twelve distinct unique partitions.

Saved mat palette and cell guides, GG007 icon/menu/site/privacy, unlimited undo/reset. Offline, no ads, analytics, account or requested permissions. Settings and completed-puzzle marks stay on device. External studio link opens browser.

Independent Python exact-cover enumeration produces all 51 legal strip tilings on this 4x3 grid; the Java oracle uses their original room assignments and set-based ray counts, without production region decoding. It agrees with production open-edge floodfill, strip bounding boxes, canonical walls, junction tests and directional room transitions on all 131072 border masks per puzzle. Exactly one solution per board; bounds, solve, undo and replay pass. Adapter navigation, saved settings, privacy, boundary taps, next, levels and persistence pass. Actual drawing pixels inspected, not phone screenshots. Phone runtime, performance and browser handoff QA incomplete. Signed TEST only, not final or Play published.

Current 803-entry registry, 131 partial recovered README records and exact Tideglass cumulative stage found no Yajitatami match. Unlike Matgrove/Tatamibari, there are no square/wide/tall symbols or general rectangles: every room is a thin strip, and each arrow digit binds its own strip length to a directional room count. Unlike Triowillow/Heteromino, rooms are not fixed three-cell shapes with same-orientation neighbor exclusions. No four-room corners is a shared rule, not a novelty claim on its own. Nondango was rejected as existing Trifen. Known Yajitatami genre, not a global invention. Partial corpus, not ALL-local. Rules: https://logic-masters.de/Raetselportal/Raetsel/zeigen.php?chlang=en&id=0008DN and http://marshall.freeshell.org/nikoli_rules.html .

Download signed test APK on MEGA: https://mega.co.nz/#!QRVUkYJA!AUVq3RieUb7aD69DdX2BOLw_haC0n9PSL_mbaxKO3tw

APK SHA256: c8a7a5ba12cff517ec78a6b3bff91366a1675963e436afae41968256aa8121e3
Full Git source upload remains pending; source is preserved in the private archive.
