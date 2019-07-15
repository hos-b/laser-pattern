# laser-pattern
modified opencv pattern tools for laser cutters

## Use

Usage example:
```bash
python gen_pattern.py -o out.svg -r 8 -c 6 -T acircles -s 42 -R 2.1 -u mm -w 600 -h 400
```
+ -o, --output - output file (default out.svg)
+ -r, --rows - pattern rows (default 11)
+ -c, --columns - pattern columns (default 8)
+ -T, --type - type of pattern, circles, acircles, checkerboard (default circles)
+ -s, --square_size - size of squares in pattern (default 20.0)
+ -R, --radius_rate - circles_radius = square_size/radius_rate (default 5.0)
+ -u, --units - mm, inches, px, m (default mm)
+ -w, --page_width - page width in units (default 216)
+ -h, --page_height - page height in units (default 279)
+ -a, --page_size - page size (default A4), supersedes -h -w arguments
+ -H, --help - show help
