# Task: Dockerize Local WordPress Site

- [ ] Analyze existing `wp-config.php` <!-- id: 0 -->
- [x] Create `docker-compose.yml` defining `wordpress`, `db`, and `phpmyadmin` services <!-- id: 1 -->
- [x] Modify `wp-config.php` to use environment variables for DB connection <!-- id: 2 -->
- [x] Start Docker containers and verify initial boot <!-- id: 3 -->
- [x] Verify database import and site functionality <!-- id: 4 -->

# Task: Configure Git Version Control

- [x] Create optimized `.gitignore` for WordPress <!-- id: 5 -->
- [x] Initialize Git repository <!-- id: 6 -->
- [x] Create initial commit with safe files <!-- id: 7 -->

# Task: Develop Custom Theme from HTML

- [x] Initialize theme structure (`style.css`, `functions.php`, `index.php`) <!-- id: 8 -->
- [x] Migrate CSS variables and global styles to `style.css` <!-- id: 9 -->
- [x] decompose HTML into `header.php`, `footer.php`, and `front-page.php` <!-- id: 10 -->
- [x] Implement mobile navigation and assets <!-- id: 11 -->

# Task: Refactor to Elementor Child Theme

- [x] Verify/Install `hello-elementor` theme <!-- id: 13 -->
- [x] Create `hello-elementor-child` with `style.css` (Custom Design) <!-- id: 14 -->
- [x] Enqueue custom styles in `functions.php` properly <!-- id: 15 -->
- [ ] Guide user to activate Child Theme and set Homepage logic <!-- id: 16 -->

# Task: Implement Instant Page Template

- [x] Create `page-landing.php` with full custom HTML <!-- id: 17 -->
- [x] Ensure CSS variables map correctly to the template <!-- id: 18 -->

# Task: Create Custom Elementor Widgets

- [x] Create `widgets/class-widget-hero.php` with editable fields <!-- id: 20 -->
- [x] Create `widgets/class-widget-solutions.php` (Repeater control) <!-- id: 21 -->
- [x] Create `widgets/class-widget-about.php` <!-- id: 22 -->
- [x] Register widgets in `functions.php` <!-- id: 23 -->
- [x] Verify widgets appear in Elementor editor <!-- id: 24 -->

# Task: Create Master Landing Widget

- [ ] Create `widgets/class-widget-landing-master.php` (All-in-one) <!-- id: 25 -->
- [ ] Register Master Widget in `functions.php` <!-- id: 26 -->
- [ ] Notify user to drag ONE widget to rule them all <!-- id: 27 -->
- [ ] Activate theme and verify against original design <!-- id: 12 -->

# Task: Sync Production to Local (Recovery)
- [ ] Confirm Server Backup Restored (User Action) <!-- id: 28 -->
- [ ] Download all files from Hostinger to Local <!-- id: 29 -->
- [ ] Commit Production State to Git Repo <!-- id: 32 -->

# Task: Chat Redesign & Fixes
- [ ] Import "Space Grotesk" font <!-- id: 34 -->
- [ ] Implement Brand Colors (#1B6E98, #011640, #0F3F54) <!-- id: 35 -->
- [ ] Update Chat UI (Tidio style, 18px text, input height fix) <!-- id: 36 -->
- [ ] Push updates to Production <!-- id: 37 -->

# Task: CI/CD Setup
- [x] Create GitHub Action `.yml` for auto-deployment <!-- id: 30 -->
- [x] Document secrets needed for GitHub Actions <!-- id: 31 -->
