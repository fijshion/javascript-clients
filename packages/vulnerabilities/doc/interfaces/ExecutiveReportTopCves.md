[@redhat-cloud-services/vulnerabilities-client](../README.md) / [Exports](../modules.md) / ExecutiveReportTopCves

# Interface: ExecutiveReportTopCves

**`Export`**

**`Interface`**

ExecutiveReportTopCves

## Table of contents

### Properties

- [cvss2\_score](ExecutiveReportTopCves.md#cvss2_score)
- [cvss3\_score](ExecutiveReportTopCves.md#cvss3_score)
- [description](ExecutiveReportTopCves.md#description)
- [known\_exploit](ExecutiveReportTopCves.md#known_exploit)
- [rule\_presence](ExecutiveReportTopCves.md#rule_presence)
- [security\_rule](ExecutiveReportTopCves.md#security_rule)
- [synopsis](ExecutiveReportTopCves.md#synopsis)
- [systems\_affected](ExecutiveReportTopCves.md#systems_affected)

## Properties

### cvss2\_score

• **cvss2\_score**: `string`

String representation of cvss2 score of the CVE.

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:970](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L970)

___

### cvss3\_score

• **cvss3\_score**: `string`

String representation of cvss3 score of the CVE.

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:976](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L976)

___

### description

• **description**: `string`

Description of the CVE.

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:982](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L982)

___

### known\_exploit

• **known\_exploit**: `boolean`

Shows whether a CVE has known exploits or not

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:988](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L988)

___

### rule\_presence

• `Optional` **rule\_presence**: `boolean`

Indicator of security rule presence

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:994](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L994)

___

### security\_rule

• `Optional` **security\_rule**: `boolean`

Indicator of security rule presence

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:1000](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L1000)

___

### synopsis

• **synopsis**: `string`

CVE synopsis

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:1006](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L1006)

___

### systems\_affected

• **systems\_affected**: `number`

Systems affected by the CVE.

**`Memberof`**

ExecutiveReportTopCves

#### Defined in

[api.ts:1012](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L1012)