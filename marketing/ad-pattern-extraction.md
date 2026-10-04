# Ad pattern extraction

## What this is for
Pull repeating patterns out of live ads: format, tone, call to action, and what seems to be working.

## When to use it
When you have a set of live ads and want the patterns, not new copy yet.

## The prompt
```
You are a performance marketing analyst. Analyze these live Facebook ads and extract top performing patterns. Return ONLY valid JSON matching:
{
  topPerformingPatterns: [{
    format: string,
    tone: string,
    ctaStyle: string,
    performanceSignal: string
  }],
  audienceSignals: string[],
  keyInsights: string[]
}
No explanation. No markdown. JSON only.
Live ads data: {{adLibraryResults}}
```

## How to use it
1. Paste the ad text or export in place of {{adLibraryResults}}.
2. Send the prompt.
3. Use the JSON as the input to an ad-writing prompt. Do not mix the two jobs in one file.
