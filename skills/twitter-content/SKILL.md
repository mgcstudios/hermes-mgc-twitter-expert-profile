---
name: twitter-content
description: Create tweets, threads, and visual content for mgcstudios Twitter. Includes templates for product updates, threads, engagement.
version: 1.0.0
platforms: [macos]
metadata:
  hermes:
    trust: official
---

# Twitter content creation for mgcstudios

## Tweet templates

### Product update
```
🎮 [App/feature name] is now available!

[Brief description in 1-2 sentences]
[Link]

#mgcstudios #impostor
```

### Behind-the-scenes
```
WIP: We just shipped [feature] 🎉

[What it does, in casual terms]
[Why it matters]

#mgcstudios #gamedev
```

### Tip / How-to
```
Pro tip 💡: [Action]

→ [Result]

#mgcstudios
```

### Community
```
[Player/feature] is 🔥

[Specific callout]

#mgcstudios
```

## Thread structure (7-tweet thread)

1. **Hook** - Big claim or question
2. **Context** - Why this matters
3. **Problem** - What was hard
4. **Solution** - How you solved it
5. **Demo** - Screenshot or video
6. **Insight** - What you learned
7. **CTA** - Try it / follow / comment

## Hashtag rules

- Max 3 hashtags per tweet
- #mgcstudios always
- App-specific: #impostor
- Industry: #gamedev, #mobilegaming, #argentinagamedev
- Tech-specific: #nostr, #webrtc, #reactnative

## Image/video rules

- Use app screenshots (capture via `xcrun simctl io ... screenshot` or `adb ... exec-out screencap`)
- Short videos: 15-60s
- Always include the mgcstudios branding
- Use high contrast, clear text overlay
- Add captions (80% of users watch muted)

## Posting checklist

Before posting:
- [ ] Spell check
- [ ] Hashtags are correct
- [ ] Image/video attached
- [ ] Link is correct (if any)
- [ ] Tone matches brand voice
- [ ] No controversial content
- [ ] Approved by Roberto (only for sensitive content)

## Tools

Use the `xurl` skill for posting, `desktop` skills for screenshots, video creation skills for shorts.
