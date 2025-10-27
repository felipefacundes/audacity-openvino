# Audacity com suporte OpenVINO

[![Versão](https://img.shields.io/badge/versão-3.7.5-blue.svg)](https://github.com/felipefacundes/audacity-openvino/releases)
[![Licença](https://img.shields.io/badge/licença-GPLv3-green.svg)](LICENSE)
[![AUR](https://img.shields.io/badge/AUR-disponível-cyan.svg)](https://aur.archlinux.org/packages/audacity-openvino-bin)

## 🎯 Sobre o Projeto

Esta é uma versão modificada do **Audacity** - o famoso editor de áudio de código aberto - com suporte integrado ao **mod-openvino**, trazendo capacidades avançadas de processamento de áudio através de inteligência artificial.

### ✨ Características Principais do Audacity

- **Editor de áudio multipista** - Trabalhe com várias faixas simultaneamente
- **Gravação em tempo real** - Capture áudio de microfone, mixers ou outras fontes
- **Edição não-destrutiva** - Experimente sem alterar o arquivo original
- **Ampla gama de efeitos** - Eco, reverberação, equalização, compressão e muito mais
- **Suporte a múltiplos formatos** - WAV, MP3, OGG, FLAC, AIFF e outros
- **Análise espectral** - Visualize e edite frequências específicas
- **Ferramentas de precisão** - Corte, copie, cole e mixe com exatidão amostral
- **Interface intuitiva** - Fácil de usar para iniciantes, poderosa para profissionais

## 🚀 Destaque Exclusivo: Suporte OpenVINO

### 🤖 Separação de Áudio com IA

O **mod-openvino** integrado permite a separação inteligente de componentes de áudio usando modelos de machine learning otimizados pela Intel:

- **🎤 Isolamento de vocais** - Extrai vozes limpas de mixagens complexas
- **🎵 Separação de instrumentos** - Isola elementos musicais individuais
- **🥁 Isolamento de bateria** - Foca nos elementos rítmicos
- **🎸 Separação de graves** - Extrai linhas de baixo com precisão

### ⚡ Performance Acelerada

O OpenVINO otimiza a inferência de modelos de IA para hardware Intel, proporcionando:

- Processamento mais rápido que soluções baseadas apenas em CPU
- Baixo consumo de recursos durante a separação de áudio
- Resultados profissionais com qualidade superior

## 📥 Instalação

### Para Usuários Arch Linux

#### 🏷️ Instalação Binária (Recomendado)

Instale a versão pré-compilada diretamente do AUR:

```bash
yay -S audacity-openvino-bin
```

#### 🔧 Instalação por Compilação

Para usuários que preferem compilar localmente:

```bash
yay -S audacity-openvino
```

### 📋 Requisitos do Sistema

- **Sistema Operacional**: Arch Linux ou derivados
- **Arquitetura**: x86_64
- **Dependências**: OpenVINO Runtime, bibliotecas de áudio padrão do Audacity
- **Espaço em disco**: ~500MB para instalação completa

## 🎨 Como Usar o OpenVINO no Audacity

1. **Abra seu arquivo de áudio** no Audacity
2. **Acesse o menu Efeitos** → **OpenVINO Separation**
3. **Selecione o modelo desejado**:
   - Vocal Separation
   - Drum Isolation  
   - Bass Extraction
   - Instrument Separation
4. **Ajuste os parâmetros** conforme necessário
5. **Processe** e aguarde a separação

## 🛠️ Desenvolvimento

### Estrutura do Projeto

```
audacity-openvino/
├── src/                    # Código fonte modificado
├── patches/               # Patches para integração OpenVINO
├── pkgbuild/             # Arquivos para construção do pacote
└── docs/                 # Documentação
```

### Compilação Manual

```bash
git clone https://github.com/felipefacundes/audacity-openvino.git
cd audacity-openvino
makepkg -si
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a **GNU General Public License v3.0** - veja o arquivo [LICENSE](LICENSE) para detalhes.

## ⚠️ Avisos Legais

- O Audacity é uma marca registrada da Muse Group
- OpenVINO é uma marca registrada da Intel Corporation
- Este projeto não é afiliado oficialmente com nenhuma das empresas mencionadas

## 📞 Suporte

- **Issues**: [GitHub Issues](https://github.com/felipefacundes/audacity-openvino/issues)
- **AUR**: [audacity-openvino-bin](https://aur.archlinux.org/packages/audacity-openvino-bin)
- **Documentação**: [Manual do Projeto](https://manual.audacityteam.org/)

---

**Nota**: Esta versão é especificamente otimizada para usuários Arch Linux que buscam uma experiência de edição de áudio aprimorada com capacidades de IA sem a necessidade de compilação manual.

---

Perfeito! Converti todo o README.md para português mantendo a estrutura profissional e todas as informações atualizadas. As principais mudanças que adaptei foram:

- **Links atualizados** para seu repositório específico
- **Versão atualizada** para 3.7.5
- **Link do AUR** corrigido para o pacote binário
- **Link de documentação** para o manual oficial do Audacity
- **Tradução completa** mantendo o tom profissional

O README agora está pronto para ser usado no seu repositório GitHub!
