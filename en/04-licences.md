# Chapter 4: Licenses

Whether you are a developer or an open source project maintainer, it is essential to have knowledge of the different types of licenses. What are your rights and duties when you use them? There are several types of licenses available to you and each may have advantages and disadvantages that should be measured before choosing. But we must remain vigilant. There may be confusion between different categories of "free" software (OSS, freeware, public domain ...) and there are dozens of free licenses, some of which are viral. This article is intended to help you understand the different features of licenses and choose the most suitable for your project.

## Free Software & Open Source

The Free Software Foundation (FSF) (www.fsf.org), an American non-profit company founded in 1985 by R. Stallman, supports the GNU operating system and manages "GPL" licenses

This foundation gives a definition of free software based on four irrevocable liberties:

- Freedom to use the software
- Freedom to copy the software. (includes the freedom to sell copies)
- Freedom to study the software. (suppose access to the source code)
- Freedom to modify the software and redistribute the modified versions.

Free license works are not always available for free and associated services (development, warranties, support, etc.) are often paid for. A work contaminated by a free license, which could initially be available only against payment, must be rebroadcast freely.

> « Think Free as Free speech and not Free beer » – R. Stallman

While the Open Source Initiative (OSI) (http://opensource.org/), an American non-profit society founded in 1998 by E. Raymond & B. Perens, promotes open source code

According to OSI, for software to be open source, its license must meet the following 10 criteria:

- Free redistribution.
- Provision of the source code.
- Allow derivative works and modifications.
- Integrity of the source code of the author.
- No discrimination between individuals or groups.
- No discrimination between the fields of application.
- No restriction on the distribution of the license (vs NDA).
- The license must not be specific to a product.
- The license must not restrict other software.
- The license must be technologically neutral.

> « Both terms describe virtually the same category of software. But they represent views based on fundamentally different values. » - R. Stallman

https://twitter.com/OpenSourceOrg/status/1174073039534706688?s=20


## Copyright, copyleft and public domain

Before presenting the different types of licenses available, it is necessary to understand the different types of rights applied to works. Here is an explanation, in simple terms, of the 3 major areas of enforcement.

**copyright** (or copyright) is a right granted to the author of the original work, including the right to authorize or prohibit the publication or distribution of their work. They protect authors from copying or unauthorized sale of their works. Copyright is granted for a limited period of time, after which the work enters the public domain.

The **public domain** includes all creations to which no exclusive intellectual property rights apply. These rights may be expired, confiscated, expressly waived or inapplicable. Copyright is generally valid until 50 to 100 years after the author's death. In simple terms, anyone can use, modify and sell these creations without permission from the author.

For example, Beethoven's compositions entered the public domain 70 years after his death in 1827. His musical compositions are available for use and sale by all.

Under **copyleft**, everyone can edit and distribute the work. This only requires one condition: the same freedom must be preserved in modified versions of the original work. People can use, modify and distribute the work as they wish. However, copyleft requires modified work to be distributed on the basis of the same license. However, it is not necessary that the copylefted content be made free as the work in the public domain.

The GNU General Public License, originally written by Richard Stallman, was the first copyleft license.


## What type of license to choose or use?

A free software always has a license (contract) of use associated, it is necessary to analyze the conditions of use, the rights and the obligations resulting from it.

To facilitate the understanding of the different types of licenses, we can classify them according to the degree of freedom they grant to the user:

- "Strong Copyleft"
- "Low Copyleft"
- "Permissive"


### Strong Copyleft

A license with a strong copyleft has **a highly contaminating character**, when the X component of a software, is under a license very copyleftée, this same license is imposed on all the software which contains this component when of its diffusion. This is known as a "contaminating" or "viral" license. It obliges to distribute the modified free software under the same license, to make available the associated source code and to distribute the entire program (free and proprietary) under the same license.

**Some strong copyleft licenses:**
- GPL: General Public License V3
- AGPL: Affero General Public License
- CC: Creative Commons declined in 6 licenses, some permissive

In the case of the GPL license, there are some explicit cases of use that do not trigger the phenomenon of contamination. Or by exception clauses included in the license. For example, the [GCC Runtime] (https://gcc.gnu.org/onlinedocs/libstdc++/manual/license.html). Either in the case of independent binaries, ie your software uses a program with the GPL license, but does not distribute it. **(PLACE AN EXAMPLE)**

Stack Overflow threads are also licensed. When you copy and paste a piece of code from the forum, it is important to know that all code snippets posted are under the CC Creative Commons license. 😱


### Low Copyleft

A license with a low copyleft **a weakly contaminating character**, it forces to distribute the modified free software under the same license and to make available the associated source code.

**Some low copyleft licenses:**
- LGPL: Lesser GPL
- EPL: Eclipse Public License
- MPL: Mozilla Public License


### Permissive

Permissive licenses offer the greatest freedom with unconditional sharing. In general, only the citation of the original authors is requested and allow any actor to change the license under which the software is distributed and without obligation of diffusion.

**Some permissive licenses:**
- BSD: Berkeley Software Distribution
- MIT: Massachussetts Institute of Technology
- Apache

There are also more esoteric permissive licenses. Like the Postcard license, whose only obligation is to send a postcard to the author. Or the [WTFPL] (http://www.wtfpl.net/) (Do What the Fuck You Want to Public License), whose title says it all. 🙂


## Conclusion

As a developer, if you use libraries or software, do not forget to check their license because it can impact your software. As an open source project maintainer, choose your license properly, whether to protect your work or its use. The website ["Choose a license"] (https://choosealicense.com/) allows you to choose your license according to your usage.