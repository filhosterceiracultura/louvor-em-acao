# Louvor em Ação — versão 1.4.0

Aplicativo PWA pessoal para organizar e tocar músicas próprias sem anúncios.

## Como testar no computador

Abra a pasta em um servidor local, por exemplo:

```bash
python3 -m http.server 4173 --directory louvor-em-acao
```

Depois, abra `http://localhost:4173` no Chrome.

## O que esta versão faz

- Importa MP3, M4A/AAC, WAV e OGG quando compatíveis com o Chrome.
- Guarda músicas localmente para reprodução offline.
- Organiza categorias, favoritos, letras, cifras e arquivo de cifra.
- Cria fila, modo aleatório, repetição e temporizador.
- O botão “Tocar agora” inicia a lista ou classificação aberta.
- Os botões “Pausar” e “Parar” controlam a música diretamente na Biblioteca.
- Grava áudio pelo microfone.
- Cria e restaura backup completo no próprio aparelho.
- É instalável como PWA.

## Sincronização

Esta versão não usa sincronização em nuvem nem serviços pagos. Para levar a
Biblioteca a outro aparelho, crie um backup completo e restaure esse arquivo no
outro aparelho.

## Publicação

Publicado gratuitamente no GitHub Pages. Abra o link em HTTPS no Chrome para
usar e instalar o aplicativo.
