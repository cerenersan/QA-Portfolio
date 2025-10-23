# Test Case Suite: Category Navigation & User Journey

**Feature:** Category & Archive Navigation
**Website:** dianxiatr.com
**Goal:** The main goal here is to ensure a smooth and intuitive journey for our readers. When a user clicks on a category, they should feel confident they're heading to the right place and can easily explore related content. This test suite verifies that all pathways related to categories work as expected.

---

| Test ID | A Human-Readable Title | Steps to Reproduce | What We Expect to Happen | Status | Priority |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Core Navigation Scenarios** | | | | | |
| **TC-CAT-01** | Clicking a main category from the menu | 1. From the homepage, hover over "Çeviriler" in the main menu.   
 2. Click on the "Dianxia Serisi" sub-item. | The user should be taken directly to the archive page for the "Dianxia Serisi" category, displaying a list of relevant posts. The page title should reflect this. | `Passed` | Highest |
| **TC-CAT-02** | Navigating between archive pages | 1. Go to a category archive with multiple pages (e.g., "Çeviriler").   
 2. Scroll to the bottom of the page.   
 3. Click the "Sonraki Sayfa" (Next Page) link. | The user should be taken to the second page of posts for that category. The content should be different from the first page. | `Passed` | High |
| **TC-CAT-03** | Jumping from a post back to its category | 1. Open any single blog post.   
 2. Locate the category link listed under the post title (e.g., "Dianxia Serisi").   
 3. Click on that category link. | The user should land on the correct category archive page, showing all posts from that category, including the one they just left. | `Passed` | High |
| **User Experience & Edge Cases** | | | | | |
| **TC-CAT-04** | Clicking a category with only one post | 1. Find and click on a category that contains only a single post. | The archive page should load correctly and display just that one post, without any layout errors or confusing messages. | `Passed` | Medium |
| **TC-CAT-05** | Visiting an empty category (if possible) | 1. Try to navigate to a category that has no posts assigned to it. | Instead of an error, the page should display a user-friendly message like "There's nothing here yet, but stay tuned!" or a similar "content not found" notice. | `Passed` | Low |
| **TC-CAT-06** | Checking footer category links | 1. Scroll to the footer of any page.   
 2. Under the "Kategoriler" section, click on any category link. | The link should navigate to the correct and corresponding category archive page, just like the main menu links. | `Passed` | Medium |

