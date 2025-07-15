# day-12 
markdown
Copy
Edit
# K-Map Simplification (VLSI Day 12)

## Summary:
- Learned how to use Karnaugh Maps (K-Map) to simplify Boolean expressions
- Practiced 2-variable and 3-variable SOP minimizations
- Converted expressions like F = A̅B + ABC̅ into minterms
- Verified F = Σ(1,3,5,7) simplifies to F = C using the K-map technique

## Files:
- `day12_kmap.txt`: Contains worked examples
- `extra_kmap_example.txt`: One extra 3-variable problem I solved
🧠 Example to include in day12_kmap.txt:
vbnet
Copy
Edit
Example 1:
F = Σ(1, 3, 5, 7)
→ Group m1 & m5 = B'C
→ Group m3 & m7 = BC
→ F = B'C + BC = C

Example 2:
F = A̅B + ABC̅
→ Terms correspond to m2, m3, m6
→ Final simplified using K-map = A̅B + ABC̅ (already minimal)
