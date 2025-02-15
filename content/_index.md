---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true

  - block: about.biography
    id: about
    content:
      # title: Biography
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Hang Zou
    design:
      columns: '2'
      view: compact


  # - block: collection
  #   # id: talks
  #   content:
  #     title: Standards
  #     text: |-
  #       - Proposed to initial a new work item about the architecture of Event-based Vision Systems...
  #       - **[Under study]** ITU-T SG21, [H.ILE-3DINR](https://www.itu.int/ITU-T/workprog/wp_item.aspx?isn=19526) "Framework and requirements of 3D reconstruction systems based on implicit neural representation for immersive live experience (ILE) services", 2024, **Main Editor**;
  #       - **[Under study]** ITU-T SG21, [F.IGreqs](https://www.itu.int/ITU-T/workprog/wp_item.aspx?isn=19288) "Requirements and framework of artificial intelligence-based image generation systems", 2024, Co-Editor;
  #       - [In force] ITU-T SG16, [F.747.15](https://www.itu.int/ITU-T/workprog/wp_item.aspx?isn=17636) (ex F.EVSreqs) "Requirements of event-based vision systems", 2022, **Main Editor**;
  #       - [In force] ITU-T SG16, [F.748.29](https://www.itu.int/ITU-T/workprog/wp_item.aspx?isn=18606) (ex F.MFDreqs) "Requirements and functions of computer audition based machinery fault diagnosis system", 2022, Co-Editor;
  #       - [In force] ITU-T SG16, [F.747.14](https://www.itu.int/ITU-T/workprog/wp_item.aspx?isn=18755) (ex F.MFSVreqs) "Requirements and capability framework of the multimodal fusion system for vision", 2022, Co-Editor;
  #       - 计划隐式三维重建新行标立项...
  #       - **[在研-草案]** CCSA TC1，《基于视频云网融合的视联网 人工智能中台》，2024，**第一起草人**；
  #       - **[在研-草案]** CCSA TC1，《基于人工智能多模态技术的信息系统技术要求 第2部分：智能交互系统》，2024-0036T-YD，**第一起草人**；
  #       - **[在研-征求意见稿]** CCSA TC1，《基于人工智能多模态技术的信息系统技术要求 第1部分：生物特征识别系统》，2023-1069T-YD，**第一起草人**；
      
  #     filters:
  #       folders:
  #         - standard
  #   design:
  #     columns: '1'
  #     view: compact


# ###########
#   - block: collection
#     content:
#       title: Patents
#       text: |-
#         - 基于联合模型的图像鉴伪方法、电子设备和存储介质，2024，**第一发明人**，2024119998511
#         - 视频压缩方法、装置、计算机可读介质及电子设备，2024，**第一发明人**，202411977968X
#         - 检索增强生成方法及装置、计算机程序产品、电子设备，2024，第四发明人，2024116885649
#         - 三维图像的合成重建方法及相关设备，2023，**第一发明人**，CN117830374A
#         - 图像生成器的训练方法、图像重建方法、装置和存储介质，2023，**第一发明人**，CN117709428A
#         - **[已授权]** 图像处理方法及装置、存储介质及电子设备，2023，**第一发明人**，CN116993590B
#         - 图像分类方法、装置、电子设备和计算机可读存储介质，2023，**第一发明人**，CN116977742A
#         - 图像处理方法、装置、计算机可读存储介质及电子设备，2023，第四发明人，CN116630514A
#         - 人体图像三维重建方法、装置、设备及存储介质，2023，**第一发明人**，CN116563467A
#         - 三维模型生成方法及装置、存储介质及电子设备，2023，第三发明人，CN116597087A
#         - 图像处理方法及装置、存储介质及电子设备，2023，第四发明人，CN116597173A
#         - **[已授权]** 模型的训练方法、训练装置、电子设备和可读存储介质，2022，**第一发明人**，CN115439610B
#         - **[已授权]** 异常数据识别模型的训练方法及相关设备，2022，**第一发明人**，CN115238805B
#         - 图像生成方法及装置、存储介质和电子设备，2022，第三发明人，CN115272576A
#         - **[已授权]** 图像生成方法及装置、存储介质和电子设备，2022，第三发明人，CN115100360B
#         - **[已授权]** 图像生成方法及装置、存储介质和电子设备，2022，第三发明人，CN115272575B
#         - **[已授权]** 图像重建方法及装置、计算机存储介质、电子设备，2022，**第一发明人**，CN115205117B
#         - 基于二维图像的三维重建方法、系统、设备及存储介质，2022，**第一发明人**，CN115018994A
#         - **[已授权]** 图像生成方法、装置、电子设备及计算机可读存储介质，2022，第三发明人，CN115063536B
#         - **[已授权]** 三维物体的图像渲染方法、装置及电子设备，2022，第三发明人，CN114863007B
#         - 图像处理方法、装置、存储介质及电子设备，2021，第二发明人，CN114332334A
#         - **[已授权]** 通用三维模型重建方法及装置、存储介质及电子设备，2021，第三发明人，CN114299252B
#         - **[已授权]** 人脸图像生成方法及装置、人脸识别方法、设备、介质，2021，**第一发明人**，CN114255502B
      
#       filters:
#         folders:
#           - patent
#     #     # exclude_featured: true
#     #     exclude_featured: false
#     design:
#       columns: '1'
#       view: list



# ###########
#   - block: collection
#     content:
#       title: Papers
#       text: |-
#         - [1] H. Zou et al., “A Unified Framework for Iris Anti-Spoofing: Introducing IrisGeneral Dataset and Masked-MoE Method,” arXiv preprint arXiv:2408.09752, 2024.
#         - [2] Q. Zhang, Q. Liu, and H. Zou, “CDNeRF: A multi-modal feature guided neural radiance fields,” presented at the CAAI International Conference on Artificial Intelligence, Springer, 2022, pp. 204–215.
#         - [3] H. Zhang, M. Zhang, Z. He, H. Zou, and R. Wang, “Coarse-to-Fine Iris Recognition Based on Multi-variant Ordinal Measures Feature Complementarity,” presented at the Biometric Recognition: 12th Chinese Conference, CCBR 2017, Shenzhen, China, October 28-29, 2017, Proceedings 12, Springer, 2017, pp. 411–419.
#         - [4] X. Hu et al., “Fine-Grained Prompt Learning for Face Anti-Spoofing,” presented at the ACM Multimedia 2024, 
#         - [5] H. Zou, H. Zhang, X. Li, J. Liu, and Z. He, “Generation textured contact lenses iris images based on 4DCycle-GAN,” presented at the 2018 24th International Conference on Pattern Recognition (ICPR), IEEE, 2018, pp. 3561–3566.
#         - [6] H. Zou et al., “La-SoftMoE CLIP for Unified Physical-Digital Face Attack Detection,” arXiv preprint arXiv:2408.12793, 2024.
#         - [7] Q. Zhang, B. H. Wang, M. C. Yang, and H. Zou, “MMNeRF: Multi-Modal and Multi-View Optimized Cross-Scene Neural Radiance Fields,” IEEE Access, vol. 11, pp. 27401–27413, 2023.
#         - [8] H. Zou et al., “Multi-angle Consistent Generative NeRF with Additive Angular Margin Momentum Contrastive Learning,” presented at the Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2024, pp. 930–939.
#         - [9] J. Guo et al., “Style-conditional Prompt Token Learning for Generalizable Face Anti-spoofing,” presented at the ACM Multimedia 2024, 



#     # filters:
#     #   folders:
#     #     - publication
#     #     # exclude_featured: true
#     #     exclude_featured: false
#     design:
#       columns: '1'
#       view: citation


---