# 如何防止女巫攻击？

1. 我们使用 **** Github 账户、短信验证、BrightID、其他一些未披露的载体，以及（很快）Idena Network/ 其他 DID 解决方案，作为 Gitcoin Grant 捐款的身份解决方案。查看您的个人资料中的信任标签，以提高您的信任度。
2. 除了 Github 原生的反女巫攻击外，我们还以编程方式检查这些账户是否有女巫攻击的迹象。根据它是女巫攻击的一部分的可能性，每个贡献都会被分配一个信任分数。现在，我们不对女巫攻击采取任何行动（除了最恶劣的情况），但我们正在悄悄地收集数据，以便在未来使用。
3. 我们使用 Vitalik Buterin 说过的 pairwise bonding 公式来抑制女巫攻击。

{% embed url="https://ethresear.ch/t/pairwise-coordination-subsidies-a-new-quadratic-funding-design/5553" %}

更多关于反女巫攻击的战略，请看：

{% embed url="https://twitter.com/owocki/status/1273458452900151296" %}
