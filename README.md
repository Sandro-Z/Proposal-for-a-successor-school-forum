# Proposal for a successor school forum (Draft)

With the waning influence and the ultimate abandonment of [Bingmayong BBS](https://bbs.xjtu.edu.cn/), XJTUers have seen a long absence of a reliable and widely-reaching on-campus platform for gathering and distributing school information and fostering student connections. Through observation and experimentation, we find it crystal clear that the demand for a successor school forum is high and urgent.

## Background

### [Bingmayong](https://bbs.xjtu.edu.cn/) is obsolescent

The technologies behind [Bingmayong](https://bbs.xjtu.edu.cn/) are obsolete and there's no reason to continue maintaining it. Additionally, the UI design is old-fashioned that it no longer aligns with the habits of modern users.

### The demands are high

We believe that the demands discussed below are urgent and should be addressed as soon as possible.

#### Demand for a hub of information exchange

Like many other Chinese organizations, information in our school is disseminated through countless group chats, which, on one hand, do not guarantee reachability for everyone in need and, on the other, cause valuable information to dissipate ultimately.

Promoters seek a widely-reaching and influencial platform to advertise their events, and recipients are eager to gather as much relevent information and seize as many opportunities as possible. Yet, apparently, both have long been dissatisfied.

#### Demand for an on-campus social platform

Growing up to be mature, thoughtful and pursuing, university students these days seek friends who share similar hobbies, values and personality and can support each other in their academic and work careers. They are no longer satisfied with the traditional classmate relationships.

Many are frustrated by the lack of opportunities to connect with like-minded peers on campus. Thus, such a social platform is in high demand.

### Limitations of existing platforms

#### [XJTU Men](https://xjtu.app/) is a flash in the pan

[Men](https://xjtu.app/) was popular for a while and well-liked by many. However, two years after its initial launch, it has only attracted 2,000 sign-ups, with a mere 20 daily active users - most of whom are from computer science or related majors - making it feel more like a niche group than a public platform.

As it is controlled and operated solely by one of our alumni - who shows no intention of expanding the user base and prefers to remain independent from the school - we believe it no longer meet our expectations for a platform that serves the broader student community.

#### Other platforms are unreliable

Other popular public online communities including [Baidu Tieba](https://tieba.baidu.com/f?kw=%E8%A5%BF%E5%AE%89%E4%BA%A4%E9%80%9A%E5%A4%A7%E5%AD%A6), Biaobaiqiang, Xiaoyuan Jishi and others are, without exception, owned and managed by external commercial entities. They allow anyone who pays to post uncensored advertisements, and may include false or harmful information.

Therefore we hold that these platforms are unreliable and should not serve as the primary arena of student public opinion.

## Objectives

### A new generation student forum

The success of [Shuiyuan SJTU](https://shuiyuan.sjtu.edu.cn) demonstrates that such a student-operated forum is not only feasible but can also thrive.

Such a forum serves more than just a space where students discuss their thoughts and the challenges they face in their studies and daily lives.

Horizontally, it helps bridge the information gap between students, providing them with more equal opportunities. Vertically, it enables the experiences and wisdom of seniors to be passed down to the future, easily retrievable through search, allowing each class of students to improve upon the previous one, rather than entering an endless cycle of confusion and struggling to find their way forward.

### A public bulletin board

Both promoters and recipients benefit from such a platform.

Covering a large portion of students, it serves as the central hub for information exchange, where promotors can easily reach their target audience. Conversely, recipients can find most of the information they care about in one place.

By allowing only on-campus or otherwise authorized individuals and organizations to post, it shields students from intrusive advertisements and misinformation.

Moreover, users can subscribe to topics and tags of interest and receive notifications whenever there are updates.

## Plan of action

### Self-hosted [Discourse](https://www.discourse.org/)

Powering [Shuiyuan](https://shuiyuan.sjtu.edu.cn), [Men](https://xjtu.app/) and many other communities, [Discourse](https://www.discourse.org/) is an out-of-the-box modern discussion platform.

We will deploy a [Discourse](https://www.discourse.org/) instance on one of the [ANA](https://xjtuana.com/) servers housed in [NIC](https://nic.xjtu.edu.cn/)'s server rooms, to ensure protection of user data and privacy.

In general, only on-campus individuals and organizations will be allowed to view and post on the forum, using their unified campus identity for login. External users must contact the site moderators to request temporary and limited access.

### O&M and technical support

We will establish a dedicated team to continuously operate, maintain and provide technical support for the platform, under the active guidance and supervision of [NIC](https://nic.xjtu.edu.cn/). New members of the team will be recruited and trained by existing ones every year.

There will be two categories of maintainers:

- **Operators**, who are required to have a basic understanding of the Internet, the Linux operating system, containerization and databases; and
- **Developers**, who are required to have basic experience in web application development and should go through [the Discourse plugin development tutorial](https://meta.discourse.org/t/developing-discourse-plugins-part-1-create-a-basic-plugin/30515).

A [GitHub](https://github.com/) organization will be created to host all plugins and additional functionalities and services, similar to [Shuiyuan on GitHub](https://github.com/ShuiyuanSJTU/).

### Moderating

A community charter will be drafted shortly after the initial launch, collectively by the early members of the community and with full consideration of input from relevant school authorities.

Moderators will then be elected and will operate in accordance with the rules and regulations set forth in the charter. They may later be dismissed by community consensus or at the direction of school authorities.

## Requirements

Support in all forms by the Network Information Center and all relevant authorities, including but not limited to:

### Official endorsement

We request that the relevant authorities recognize this platform as the successor to [Bingmayong](https://bbs.xjtu.edu.cn/) and support the necessary administrative procedures for it to operate as an official school application.

### Advertisement

We should have the freedom to promote the platform both online and offline. Addionally, it would be beneficial if a flyer can be included in the admission letter, encouraging newly admitted students to join the student community as soon as possible.

### Intervene only when necessary

As previously stated, school authorities retain the full right to completely take over the platform. However, under normal circumstances, the platform's relative autonomy as a student-operated community should be respected.

Authorities are encouraged to offer guidance when appropriate and step in only when necessary. When intervention is performed, the necessity should be clearly justified to the community.

## Call to action

We reaffirm that the demands are urgent and should be addressed as soon as possible, and such a platform will benefit students for years to come. By comparing [Shuiyuan](https://shuiyuan.sjtu.edu.cn) and [Men](https://xjtu.app/), it becomes clear that such success can't be achieved without the support of school authorities.

There are many, within [ANA](https://xjtuana.com/) and beyond, who are willing to change the current situation and improve our school lives. Thus we once again request your support.

---

*Originally proposed collectively by members of*  
*the Development Team <xjtuana-devel@googlegroups.com>*  
*XJTU Association of Network Administrators*  
*(a student organization under the supervision of [NIC]((https://nic.xjtu.edu.cn/)))*  
*in April 2025*
