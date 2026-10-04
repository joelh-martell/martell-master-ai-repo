# Brand profile from a website

## What this is for
A structured read of a website: tone, value props, calls to action, audience signals, and colors.

## When to use it
When you need a brand profile as JSON before you write ads. Writing the ads is a different prompt.

## The prompt
```
You are a brand strategist. Analyze this website content and return ONLY valid JSON matching this exact schema:
{
  tone: string[],
  valueProps: string[],
  ctaPatterns: string[],
  audienceSignals: string[],
  colorPalette: string[]
}
No explanation. No markdown. JSON only.
Website content: {{content}}
```

## How to use it
1. Paste the page text in place of {{content}}.
2. Send the prompt.
3. Keep the JSON. Do not ask for a paragraph if you still need this shape.
