# Ad creatives from patterns

## What this is for
Write Facebook ad creatives for one brand by copying the structure of another brand’s strongest patterns.

## When to use it
After you already have a source brand profile, a target brand profile, and the pattern notes. This does not research the site or the ad library.

## The prompt
```
You are a world-class Facebook ad copywriter.
Source brand profile: {{sourceProfile}}
Target brand profile: {{targetProfile}}
Top performing patterns from source live ads: {{patterns}}
Key insights from source ad library: {{insights}}

Generate {{count}} Facebook ad creatives for the target brand.
Model the tone, CTA style, and structure on the source brand's strongest patterns but adapt all messaging to fit the target brand's value props and audience.

Return ONLY a valid JSON array. No explanation. No markdown. JSON only.
Schema for each item:
[{
  headline: string (max 40 chars),
  primaryText: string (max 125 chars),
  description: string (max 30 chars),
  cta: string,
  targetAudience: {
    name: string,
    interests: string[],
    ageRange: [number, number],
    estimatedReach: string
  },
  confidenceScore: number (0-100),
  rationale: string
}]
```

## How to use it
1. Fill every {{placeholder}} from the brand-profile and pattern prompts, or from your own notes.
2. Set {{count}}.
3. Review the rationale before you run anything.
