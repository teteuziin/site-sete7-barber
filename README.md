# Site — Sete7 Barber · SETE7 ACADEMY · Nautillus Barber Club (nº7, fase 2)

⚠️ **NÃO PUBLICAR sem aprovação do usuário.** Pacote local aguardando aprovação; a prévia é o artefato web hospedado `sete7-barber-previa-do-site`.

## Conceito
**"Do Desgracê ao Mestre Barbeiro"** — o arco do aluno Antony (o viral em que ele erra → a evolução → a formatura com o certificado "MESTRE BARBEIRO") como espinha narrativa do funil do curso. Dois mundos visuais num site só: **SETE7 ACADEMY em preto + amarelo** (identidade das artes do curso) e **Nautillus Barber Club em dourado náutico** (o escudo da loja). Dois funis: vender o curso e encher a barbearia.

## Fatos usados (fontes no dossiê: ~/workspace/prospeccao/sete7-barber-portfolio/README.md)
- Dono/decisor único: Celso Silva dos Santos ("artista da autoestima"), Pau da Lima, Salvador/BA.
- Curso presencial de barbeiro: **R$ 1.800** (arte oficial de 22/01/2026) — **único valor em R$ do site**. 100% prático, certificado incluso, turmas limitadas; conteúdo: máquina e tesoura, degradê, barba, sobrancelha, pigmentação, biossegurança.
- Matrícula: WhatsApp do curso **(71) 99155-1459** (público, impresso nas artes oficiais) — o montador abre `wa.me/5571991551459` com a mensagem montada.
- Barbearia: serviços **sem nenhum preço** (nenhum preço de barbearia é público). Agendamento pelo telefone da loja **(71) 99148-9704** via `tel:` — ⚠️ esse número consta na ficha do Google **sem rótulo de WhatsApp** e NÃO é apresentado como WhatsApp em nenhum ponto do site.
- Endereço divulgado por eles: Mercantil Rodrigues (antigo G Barbosa), Rua Jayme Vieira Lima, Pau da Lima, Salvador/BA, em frente à Mansão do Caminho, piso superior. (A ficha do Google usa a rua lateral, Ismar Araújo, 168 — divergência registrada no dossiê; o site usa o endereço que ELE divulga.)
- Horários (seg 9h–19h, ter–sáb 9h–20h, dom 9h–12h): **fonte = ficha do Google da Nautillus Barber Club** (eles não publicam horários no Instagram).
- Seguidores: "mais de 41 mil" (divergência 41.121 × 44K registrada no dossiê). Prova social = Instagram (330 mil curtidas e 6,2 mil comentários no viral; 42 mil na evolução; 13 mil e 12 mil nos tutoriais). Nota do Google NÃO usada (não exposta nas fontes).
- Grafia oficial da loja: **Nautillus** (LL), conforme ficha do Google e o handle @nautillusbarberclub_.

## Mídias — decisões registradas
- **09-arte-black-friday.jpg — EXCLUÍDA.** A arte contém a oferta VENCIDA da Black Friday (R$ 500, válida até 15/11/2026) com o preço em destaque máximo; exibi-la violaria a regra de preço único (R$ 1.800).
- **02-arte-curso.jpg — EXCLUÍDA (inteira e em recorte).** A arte tem a oferta vigente em texto embutido (duplicaria preço/conteúdo do site) e os dois recortes tentados do retrato do Celso arrastaram fragmentos legíveis do texto da arte ("CURSO DE BARBEIRO", "CERTIFICADO"), violando a regra de imagens limpas. O Celso aparece no site pela foto de perfil da conta-mãe e pelos vídeos.
- **03-tour-barbearia-08/09/10.mp4 — slides AMBIENTES mudos do carrossel.** Vieram sem faixa de áudio na descarga (confirmado por ffprobe) e o re-download com áudio não chegou a tempo da montagem; entram apenas como slides ambientes em autoplay mudo em loop do carrossel do tour — nunca como players de som.
- **Tutoriais 06/13 — identidade CONFIRMADA pelos frames, sem troca:** 06 = low fade medido nos dedos (dedo indicando os níveis na têmpora, fade baixo); 13 = degradê com duas marcações (as duas linhas de marcação visíveis antes do blend).
- Vídeos 360×640 (04, 11, 12, 18) exibidos contidos em moldura estreita (máx. 312px), nunca esticados.
- Logo transparente da Nautillus gerada de `marca/logo-perfil-nautillus.jpg` (flood-fill a partir das bordas sobre o fundo carvão uniforme; interior do escudo e tesouras preservados). A "logo" da conta-mãe (`marca/logo-perfil-sete7.jpg`) é uma FOTO do Celso — usada como retrato no hero; a marca-mãe é wordmark tipográfico.

## Estrutura
`index.html` + `media/` (20 vídeos, 7 fotos do tour, retrato do Celso, logo transparente, 20 pôsteres de frames reais em `media/posters/`). Nenhum arquivo acima de 25 MB; vídeos como arquivos .mp4 reais (nada de base64/data URI).
