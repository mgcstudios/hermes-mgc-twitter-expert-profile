# Hermes Twitter Expert Profile

This is the **Twitter expert** profile for mgcstudios on Hermes.

## What it does

Manages the mgcstudios Twitter account:
- Creates tweets, threads, replies
- Generates images and videos of the app
- Engages with the community
- Monitors competitors and trends
- Tracks engagement metrics

## Install

This profile is installed via Hermes. See the [Hermes install repo](https://github.com/mgcstudios/hermes) for installation instructions.

```bash
# Install Hermes (from the install repo)
git clone git@github.com:mgcstudios/hermes.git
cd hermes
./install.sh

# Install the Twitter expert profile
hermes profile install twitter-expert
```

## Configuration

Set the following environment variables:
- `TWITTER_API_KEY`
- `TWITTER_API_SECRET`
- `TWITTER_BEARER_TOKEN`
- `TWITTER_ACCESS_TOKEN`
- `TWITTER_ACCESS_SECRET`

## Files

- `SOUL.md` - personality + boundaries
- `AGENTS.md` - operational autonomy rules
- `config.yaml` - profile configuration
- `skills/` - reusable skills (xurl, image generation, video creation, etc.)
