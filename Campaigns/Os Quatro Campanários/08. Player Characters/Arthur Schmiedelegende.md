---
Calço: 2837
Monótono: 283.7
Jota: 28.369999999999997
Talento: 2.8369999999999997
Marco: 0.28369999999999995
Centa: 436.46153846153845
Centavo: 218.23076923076923
Bit: 87.29230769230769
QBit: 43.646153846153844
Roda: 10.911538461538461
Real: 4.364615384615385
Moe: 2269.6
Ferro: 907.8399999999999
Cobre: 453.91999999999996
Prata: 45.391999999999996
Republica: 3.782666666666666
---

```RpgManager4
id: 
  type: "playercharacter"
  campaign: "Campaigns/Os Quatro Campanários/Os Quatro Campanários.md"
tasks: []
images: 
  - path: "Assets/Arthur Schmiedelegende 2.png"
    caption: "Eu Mesmo"
data: 
  description: "Arthur era um jovem nascido na movimentada cidade de Lature, localizada ao lado de um vulcão ativo no Império Arturiano. A cidade era conhecida por seus ricos depósitos de minerais que eram minerados e usados para criar poderosas armas para a guerra contínua contra demônios. Lature também era conhecida como o berço dos ferreiros mais habilidosos do império.\n\nApesar de crescer em uma cidade cheia de artesãos talentosos e guerreiros, Arthur sentia que não se encaixava completamente. Ele não era o melhor ferreiro nem o mais forte mineiro, e frequentemente se perguntava qual era seu verdadeiro propósito na vida.\n\nEm um dia fatídico, um homem misterioso da Universidade, uma instituição de prestígio conhecida por seus estudos avançados em ciência e magia, visitou Lature. Intrigado pela natureza inquisitiva de Arthur e sua sede de conhecimento, o homem o apresentou ao conceito de \"simpatia\".\n\nA simpatia era uma forma rara e poderosa de magia que permitia às pessoas estabelecerem conexões profundas com o mundo ao seu redor, semelhante ao emaranhamento quântico. O homem da Universidade viu um grande potencial em Arthur e o convidou a estudar na instituição, onde ele poderia dominar e aprimorar essa habilidade única.\n\nDeterminado a descobrir sua verdadeira vocação, Arthur aceitou a oferta do homem e embarcou em uma jornada rumo à Universidade. No caminho, o homem ensinou a Arthur os princípios básicos.\n\nApesar de enfrentar muitos desafios e dúvidas ao longo do caminho, o talento natural e a determinação inabalável de Arthur impressionaram os professores da Universidade, Fazendo ele ser aprovado na Universidade."
  _anotaes: "flor rosa azulada localizada entre o I e o T no mapa."
  _altura: "1,98 m"
  _peso: "110 kg"
```

[[Campaigns/Os Quatro Campanários/Os Quatro Campanários.md|]]

Calço:`INPUT[number():Calço]`
[Monótono:: `VIEW[number({Calço}/10)][math:Monótono]`]
[Jota:: `VIEW[number({Monótono}/10)][math:Jota]`]
[Talento:: `VIEW[number({Jota}/10)][math:Talento]`]
[Marco:: `VIEW[number({Talento}/10)][math:Marco]`]
	
[Centa:: `VIEW[number({Calço}/6.5)][math:Centa]`]
[Centavo:: `VIEW[number({Centa}/2)][math:Centavo]`]
[Bit:: `VIEW[number({Centavo}/2.5)][math:Bit]`]
[Quarterbit:: `VIEW[number({Bit}/2)][math:QBit]`]
[Roda:: `VIEW[number({QBit}/4)][math:Roda]`]
[Real:: `VIEW[number({QBit}/10)][math:Real]`]

[Moe:: `VIEW[number({Calço}/1.25)][math:Moe]`]
[Ferro:: `VIEW[number({Moe}/2.5)][math:Ferro]`]
[Cobre:: `VIEW[number({Ferro}/2)][math:Cobre]`]
[Prata:: `VIEW[number({Cobre}/10)][math:Prata]`]
[Republica:: `VIEW[number({Prata}/12)][math:Republica]`]