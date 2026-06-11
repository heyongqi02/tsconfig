# @heyongqi/tsconfig

A collection of shared TypeScript configuration presets.

## Install

```bash
pnpm add -D @heyongqi/tsconfig typescript
```

## Usage

Reference a preset via `extends` in your `tsconfig.json`:

```json
{
  "extends": "@heyongqi/tsconfig/configs/node24/library/tsconfig.json"
}
```

## Available presets

| Preset                                 | Description                     |
| -------------------------------------- | ------------------------------- |
| `configs/node24/library/tsconfig.json` | Config for Node.js 24 libraries |
