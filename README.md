# 🎨 Color Correction by Lucas

Um nó personalizado para ComfyUI que oferece controles avançados de correção de cores, ruído e desfoque.

## ✨ Funcionalidades

Este nó permite ajustar os seguintes parâmetros de uma imagem:

- 🌈 **Hue (Matiz)**: Ajusta a tonalidade das cores (-180° a +180°)
- 💧 **Saturation (Saturação)**: Controla a intensidade das cores (0 a 3x)
- 💡 **Brightness (Brilho)**: Ajusta o brilho geral da imagem (0 a 3x)
- 🔆 **Contrast (Contraste)**: Controla a diferença entre áreas claras e escuras (0 a 3x)
- ⚡ **Gamma**: Ajusta o brilho dos tons médios (0.1 a 3.0)
- 📺 **Noise (Ruído)**: Adiciona ruído aleatório à imagem (0 a 1)
- 🌫️ **Blur (Desfoque)**: Aplica desfoque gaussiano (0 a 10 pixels)

## 📦 Instalação

### Método 1: Instalação Manual

1. Baixe o arquivo `color_correction_by_lucas.zip`
2. Extraia o conteúdo na pasta `custom_nodes` do seu ComfyUI:
   ```
   ComfyUI/custom_nodes/color_correction_by_lucas/
   ```
3. Reinicie o ComfyUI

### Método 2: Via ComfyUI Manager (se disponível)

1. Abra o ComfyUI Manager
2. Procure por "Color Correction by Lucas"
3. Clique em "Install"
4. Reinicie o ComfyUI

## 🚀 Como Usar

1. No ComfyUI, procure por "Color Correction by Lucas" na categoria `image/color`
2. Adicione o nó ao seu workflow
3. Conecte uma imagem à entrada do nó
4. Ajuste os parâmetros usando os sliders:
   - **Hue**: Valores negativos movem para o vermelho, positivos para o azul
   - **Saturation**: 0 = preto e branco, 1 = normal, >1 = mais saturado
   - **Brightness**: 0 = preto, 1 = normal, >1 = mais brilhante
   - **Contrast**: 0 = cinza uniforme, 1 = normal, >1 = mais contraste
   - **Gamma**: <1 = mais escuro, 1 = normal, >1 = mais claro
   - **Noise**: 0 = sem ruído, >0 = adiciona ruído aleatório
   - **Blur**: 0 = sem desfoque, >0 = aplica desfoque gaussiano
5. A imagem corrigida será disponibilizada na saída

## 🎯 Presets Incluídos

O nó inclui presets pré-configurados acessíveis via menu do botão direito:

- **🔄 Reset All Values**: Restaura todos os valores padrão
- **🎯 Enhance Colors**: Melhora cores e contraste
- **🌙 Vintage Look**: Aplica um visual vintage com ruído e desfoque sutil

## 🎨 Interface Visual

- **Sliders Coloridos**: Interface visual aprimorada com gradientes
- **Ícones Visuais**: Cada parâmetro tem um ícone identificador
- **Menu Contextual**: Acesso rápido a presets e informações
- **Assinatura do Autor**: "by Lucas" visível no nó

## 🔧 Funcionalidades da Interface

- **Reset All Values**: Clique com o botão direito no nó e selecione "🔄 Reset All Values"
- **About**: Clique com o botão direito e selecione "ℹ️ About Color Correction"
- **Presets**: Acesse configurações pré-definidas via menu contextual

## 📋 Requisitos

- ComfyUI
- Python 3.8+
- PyTorch 2.0+
- PIL (Pillow)
- OpenCV (cv2)
- NumPy

## 🐛 Solução de Problemas

### O nó não aparece na lista
- Verifique se a pasta foi extraída corretamente em `custom_nodes`
- Reinicie completamente o ComfyUI
- Verifique o console para mensagens de erro

### Erro "module 'cv2' has no attribute..."
- Instale o OpenCV: `python -m pip install opencv-python`
- Use o Python específico do ComfyUI para instalação

### Performance lenta
- Para imagens muito grandes, considere redimensionar antes da correção
- Ajustes de gamma e blur podem ser mais lentos em imagens de alta resolução

## 💡 Dicas de Uso

- **Para fotos escuras**: Aumente brightness e ajuste gamma
- **Para fotos desbotadas**: Aumente contrast e saturation
- **Para correção de cor**: Ajuste hue sutilmente
- **Para efeitos artísticos**: Combine múltiplos ajustes
- **Para look vintage**: Use o preset "Vintage Look" ou ajuste manualmente noise e blur

## 📝 Changelog

### v1.0.0
- Lançamento inicial
- Suporte para HUE, Saturation, Brightness, Contrast, Gamma, Noise e Blur
- Interface visual personalizada com sliders coloridos
- Presets pré-configurados
- Suporte para processamento em lote

## 👨‍💻 Autor

Criado com ❤️ por **Lucas**

## 📄 Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir novas funcionalidades
- Enviar pull requests

## 📞 Suporte

Se você encontrar algum problema ou tiver dúvidas, por favor:
1. Verifique a seção de solução de problemas acima
2. Procure por issues similares no repositório
3. Crie uma nova issue com detalhes do problema

---

**Aproveite a correção de cores! 🎨**
