---
name: twitter-browser
description: Use computer-use skill to drive a real browser for Twitter interactions that xurl CLI cannot do. Use as fallback or for visual verification.
version: 1.0.0
platforms: [macos]
metadata:
  hermes:
    trust: official
---

# Twitter via browser (computer-use)

When xurl CLI can't do something, or Roberto wants to verify visually, use the browser.

## When to use browser over xurl

- Visual verification (take screenshot before posting)
- Complex Twitter web interactions
- Twitter Spaces
- Resolving UI bugs (e.g., a button that doesn't work)
- Reading protected accounts
- Cross-checking analytics dashboard

## Browser automation basics

Use the `computer-use` skill to drive a real browser. The skill handles:
- Mouse clicks
- Keyboard input
- Scrolling
- Screenshots

## Common flows

### Login to Twitter
1. Open `https://x.com/i/flow/login`
2. Enter Roberto's credentials (ask for them if needed)
3. Solve 2FA if prompted
4. Stay logged in

### Post a tweet
1. Navigate to `https://x.com/home`
2. Click on the "What's happening?" textbox
3. Type the tweet text
4. Click "Post"
5. Take screenshot to verify

### Reply to a tweet
1. Navigate to the tweet URL
2. Click the reply icon
3. Type the reply
4. Click "Reply"
5. Take screenshot

### Post a thread
1. Start a tweet as above
2. Click the "+" (add to thread) icon
3. Type next tweet
4. Repeat until done
5. Click "Post all"

### Upload media
1. Click the media icon (image/video)
2. Select file
3. Wait for upload
4. Add text
5. Click "Post"

## Tips for browser-based Twitter

- Always take a screenshot before and after important actions
- Use specific CSS selectors or accessible names (x.com is reasonably accessible)
- Don't click random things - use the keyboard shortcuts (g+t for new tweet, etc.)
- Be patient - browser automation is slower than xurl

## When NOT to use browser

- Bulk operations (use xurl)
- Repetitive tasks (use xurl with shell scripts)
- Time-sensitive posting (use xurl, browser is slower)

## Auth (one-time)

Roberto needs to log in once on the Mac. The browser will use the session cookies.

For automation:
1. Open Chrome
2. Go to x.com
3. Log in with mgcstudios86@gmail.com (or Roberto's account)
4. Stay logged in
5. The automation will pick up the session

## Self-sufficiency

You have both xurl (API) and computer-use (browser). Default to xurl, fall back to browser for complex cases.
