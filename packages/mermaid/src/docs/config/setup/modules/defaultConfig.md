# Module: defaultConfig

## Variables

### <a id="configkeys" name="configkeys"></a> configKeys

• `Const` **configKeys**: `string`[]

#### Defined in

defaultConfig.ts:1869

---

### <a id="default" name="default"></a> default

• `Const` **default**: `Partial`<`MermaidConfig`\>

**Configuration methods in Mermaid version 8.6.0 have been updated, to learn more[[click
here](8.6.0_docs.md)].**

## **What follows are config instructions for older versions**

These are the default options which can be overridden with the initialization call like so:

**Example 1:**

```js
mermaid.initialize({ flowchart: { htmlLabels: false } });
```

**Example 2:**

```html
<script>
  const config = {
    startOnLoad: true,
    flowchart: { useMaxWidth: true, htmlLabels: true, curve: 'cardinal' },
    securityLevel: 'loose',
  };
  mermaid.initialize(config);
</script>
```

A summary of all options and their defaults is found [here](#mermaidapi-configuration-defaults).
A description of each option follows below.

#### Defined in

defaultConfig.ts:33