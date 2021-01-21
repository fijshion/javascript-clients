[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [VulnerabilitiesPostOutAttributes](vulnerabilitiespostoutattributes.md)

# Interface: VulnerabilitiesPostOutAttributes

**`export`** 

**`interface`** VulnerabilitiesPostOutAttributes

## Hierarchy

* **VulnerabilitiesPostOutAttributes**

## Index

### Properties

* [cvss_score](vulnerabilitiespostoutattributes.md#cvss_score)
* [impact](vulnerabilitiespostoutattributes.md#impact)
* [synopsis](vulnerabilitiespostoutattributes.md#synopsis)

## Properties

###  cvss_score

• **cvss_score**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:2120](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L2120)*

String representation of cvss3 or cvvs2 (if v3 is not present) score of the CVE.

**`memberof`** VulnerabilitiesPostOutAttributes

___

###  impact

• **impact**: *string*

*Defined in [packages/vulnerabilities/git-api/api.ts:2126](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L2126)*

Red Hat security impact of the CVE.

**`memberof`** VulnerabilitiesPostOutAttributes

___

###  synopsis

• **synopsis**: *string*

*Defined in [packages/vulnerabilities/git-api/api.ts:2132](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L2132)*

Synopsis of the CVE.

**`memberof`** VulnerabilitiesPostOutAttributes