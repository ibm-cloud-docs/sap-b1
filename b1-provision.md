---

copyright:
  years: 2019, 2020
lastupdated: "2020-07-21"

keywords: SAP Business One

subcollection: sap-b1

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .note}

# Provisioning SAP Business One
{: #provision}

SAP Business One has been certified to run on {{site.data.keyword.baremetal_long}}.
{: shortdesc}

## SAP Business One on SAP HANA
{: #run-on-hana}

The following table is a list of {{site.data.keyword.baremetal_short}} certified to run SAP Business One on HANA in the {{site.data.keyword.cloud}}. For information on how to decipher the server name, see [Determining your SAP HANA configuration](/docs/sap-hana?topic=sap-hana-determine_configuration).

All the listed servers have been certified for the SLES 12 SP4 operating system only at this time.
{: note}

| **Server type** | **Cores** | **RAM** |
| --- | --- | --- | --- |
| [BI.S3.H2.192](http://ibm.biz/S3_H2_192_B1){: external} | 36 | 192 GB |
| [BI.S3.H2.384](http://ibm.biz/S3_H2_384_B1){: external} | 36 | 384 GB |
| [BI.S3.H2.768](http://ibm.biz/S3_H2_768_B1){: external} | 36 | 768 GB |
| [BI.S4.H2.192 Appliance](http://ibm.biz/S4_H2_192_B1){: external} | 32 | 192 GB |
| [BI.S4.H2.384 Appliance](http://ibm.biz/S4_H2_384_B1){: external} | 32 | 384 GB |
| [BI.S4.H2.768 Appliance](http://ibm.biz/S4_H2_768_B1){: external} | 40 | 768 GB |
{: caption="Table 1. SAP HANA servers for SAP Business One" caption-side="top"}

## SAP Business One on Microsoft SQL
{: #run-on-premises}

The following table is a list of the SAP NetWeaver-certified servers that have been certified to run SAP Business One. For information on how to decipher the server name, see [Setting up your SAP NetWeaver infrastructure](/docs/sap-netweaver?topic=sap-netweaver-set_up_infrastructure).

lists the supported Microsoft Windows Server versions for these SAP Business One server platforms.

For a list of Microsoft Windows Server versions supported for the following SAP Business One server platforms, see the [SAP Business One Platform Support Matrix](https://help.sap.com/doc/011000358700000032462013e/9.3/en-US/B1_Platform_Support_Matrix.pdf){: external}.
{: note}

| **Server type** | **Cores** | **RAM** |
| --- | --- | --- | --- |
| [BI.S3.NW32 (OS Options)](http://ibm.biz/S3_NW32_B1){: external} | 4 | 32 GB |
| [BI.S3.NW64 (OS Options)](http://ibm.biz/S3_NW64_B1){: external} | 4 | 64 GB |
| [BI.S3.NW192 (OS Options)](http://ibm.biz/S3_NW192_B1){: external} | 36 | 192 GB |
| [BI.S4.NW192 (OS Options)](http://ibm.biz/S4_NW192_B1){: external} | 32 | 192 GB |
| [BI.S4.NW384 (OS Options)](http://ibm.biz/S4_NW384_B1){: external} | 32 | 384 GB |
| [BI.S4.NW768 (OS Options)](http://ibm.biz/S4_NW768_B1){: external} | 40 | 768 GB |
{: caption="Table 1. SAP NetWeaver servers for SAP Business One " caption-side="top"}

More information can be found in [SAP Notes 2058870](https://launchpad.support.sap.com/#/notes/2058870){: external} and [2586742](https://launchpad.support.sap.com/#/notes/2586742){: external}, and [SAP Business One How-to Guides](https://help.sap.com/viewer/83196e2e80d941d798668e7c34568832/9.3/en-US){: external}.

## Training
{: #training}

There is training on the integration framework for SAP Business One. The self-paced, online course takes you through scenario design basics, the integration of SAP Business One, and integrating the SAP Business One database. For more information on the course, click [here](https://open.sap.com/courses/ifb1){: external}.

Training is also available on the different SAP Business One modules. For more information on the courses, see [SAP Training](https://training.sap.com/search?filters%5Btraining_path%5D%5BTraining+Path%5D=on&q=){: external}. Enter *SAP Business One* in the Search bar to narrow your search to courses specific to SAP Business One.

## Next Steps
{: #next-steps-provision}

* [Managing SAP Business One](/docs/sap-b1?topic=sap-b1-manage#manage)
