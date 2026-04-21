---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

### See full list at [Google Scholar](https://scholar.google.com/citations?user=7DnpUlIAAAAJ). ($\*$: co-first author;  ^: corresponding author; #: project leader)

<table style="width:100%;border:None;border-spacing:0px;border-collapse:separate;margin-right:0;margin-left:0;font-size:0.95em;">
  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>DuQuant: Distributing Outliers via Dual Transformation Makes Stronger Quantized LLMs.</b> 
      <br>
      <u>Haokun Lin*</u>, Haobo Xu*, Yichen Wu*, Jingzhi Cui, Yingtao Zhang, Linzhan Mou, Linqi Song, Zhenan Sun^, Ying Wei^,
      <br>
      <i>in 38th Conference on Neural Information Processing Systems (<b>NeurIPS 2024 Oral</b>)</i>. 
      <br>
      [<a href="https://arxiv.org/pdf/2406.01721">PDF</a>]
      [<a href="https://arxiv.org/abs/2406.01721">arXiv</a>]
      [<a href="https://duquant.github.io/">Project</a>]
      [<a href="https://github.com/Hsu1023/DuQuant">Github</a>]
      [<a href="https://mp.weixin.qq.com/s/lM4HeylIivW8c2o5f6J8wg">QbitAI/量子位</a>] 
      <!-- [<a href="https://scholar.googleusercontent.com/scholar.bib?q=info:7ed_gRMZ2K8J:scholar.google.com/&output=citation&scisdr=ClGb7WsHEJj5ikR5kvs:AFWwaeYAAAAAZ_t_ivuNiaHr_MEN49QUocTVDlA&scisig=AFWwaeYAAAAAZ_t_isLaMkGx5aFWqySHBsqSer8&scisf=4&ct=citation&cd=-1&hl=en">bibtex</a>] -->
      [<a href="#" onclick="showBibDuquant()">bibtex</a>]
      <script>
        function showBibDuquant() {
          const bib = `@article{lin2024duquant,\n
  title={Duquant: Distributing outliers via dual transformation makes stronger quantized llms},\n
  author={Lin, Haokun and Xu, Haobo and Wu, Yichen and Cui, Jingzhi and Zhang, Yingtao and Mou, Linzhan and Song, Linqi and Sun, Zhenan and Wei, Ying},\n
  journal={Advances in Neural Information Processing Systems},\n
  volume={37},\n
  pages={87766--87800},\n
  year={2024}\n
}`;
          const newWindow = window.open("", "duquant_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>MoPE-CLIP: Structured Pruning for Efficient Vision-Language Models with Module-wise Pruning Error Metric.</b>
      <br>
      <u>Haokun Lin</u>, Haoli Bai, Zhili Liu, Lu Hou, Muyi Sun, Linqi Song, Ying Wei^, Zhenan Sun^,
      <br>
      <i>in IEEE / CVF Computer Vision and Pattern Recognition Conference 2024 (<b>CVPR 2024</b>).</i>
      <br>
      [<a href="https://arxiv.org/pdf/2403.07839">PDF</a>]
      [<a href="https://arxiv.org/abs/2403.07839">arXiv</a>] 
      [<a href="#" onclick="showBibMope()">bibtex</a>]
      <script>
        function showBibMope() {
          const bib = `@inproceedings{lin2024mope,\n
  title={Mope-clip: Structured pruning for efficient vision-language models with module-wise pruning error metric},\n
  author={Lin, Haokun and Bai, Haoli and Liu, Zhili and Hou, Lu and Sun, Muyi and Song, Linqi and Wei, Ying and Sun, Zhenan},\n
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},\n
  pages={27370--27380},\n
  year={2024}\n
}`;
          const newWindow = window.open("", "mope_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>TokLIP: Marry Visual Tokens to CLIP for Multimodal Comprehension and Generation.
      </b> 
      <br>
      <u>Haokun Lin*</u>, Teng Wang*, Yixiao Ge^, Yuying Ge, Zhichao Lu, Ying Wei, Qingfu Zhang, Zhenan Sun, Ying Shan,
      <br>
      <i>Preprint.</i>
      <br>
      [<a href="https://arxiv.org/pdf/2505.05422">PDF</a>]
      [<a href="https://arxiv.org/abs/2505.05422">arXiv</a>]
      [<a href="https://github.com/TencentARC/TokLIP">Github</a>]
      [<a href="https://huggingface.co/TencentARC/TokLIP">HuggingFace</a>]
      [<a href="https://mp.weixin.qq.com/s/o9nXvLmpZ9gTtGTmZsQIRQ">QbitAI/量子位</a>] 
      [<a href="#" onclick="showBibTok()">bibtex</a>]
      <script>
        function showBibTok() {
          const bib = `@article{lin2025toklip,\n
  title={Toklip: Marry visual tokens to clip for multimodal comprehension and generation},\n
  author={Lin, Haokun and Wang, Teng and Ge, Yixiao and Ge, Yuying and Lu, Zhichao and Wei, Ying and Zhang, Qingfu and Sun, Zhenan and Shan, Ying},\n
  journal={arXiv preprint arXiv:2505.05422},\n
  year={2025}\n
}`;
          const newWindow = window.open("", "toklip_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
       <b>Quantization Meets dLLMs: A Systematic Study of Post-training Quantization for Diffusion LLMs.
       </b> 
      <br>
      <u>Haokun Lin*</u>, Haobo Xu*, Yichen Wu, Ziyu Guo, Renrui Zhang, Zhichao Lu, Ying Wei, Qingfu Zhang, Zhenan Sun,
      <br>
      <i>in Machine Intelligence Research, 2025.</i>
      <br>
      [<a href="https://arxiv.org/pdf/2508.14896">PDF</a>]
      [<a href="https://arxiv.org/abs/2508.14896">arXiv</a>]
      [<a href="https://github.com/FelixMessi/QDLM">Github</a>]
      <!-- [<a href="https://huggingface.co/TencentARC/TokLIP">HuggingFace</a>] -->
      [<a href="#" onclick="showBibQDLM()">bibtex</a>]
      <script>
        function showBibQDLM() {
          const bib = `@article{lin2025quantization,\n
  title={Quantization Meets dLLMs: A Systematic Study of Post-training Quantization for Diffusion LLMs},\n
  author={Lin, Haokun and Xu, Haobo and Wu, Yichen and Guo, Ziyu and Zhang, Renrui and Lu, Zhichao and Wei, Ying and Zhang, Qingfu and Sun, Zhenan},\n
  journal={arXiv preprint arXiv:2508.14896},\n
  year={2025}\n
}`;
          const newWindow = window.open("", "qdlm_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
       <b>Efficient Diffusion Language Models: A Comprehensive Survey.
       </b> 
      <br>
      <u>Haokun Lin*#</u>, Xinle Jia*, Shaozhen Liu*, Shujun Xia*, Weitao Huang*, Haobo Xu, Junyang Li, Yicheng Xiao, Xingrun Xing, Ziyu Guo, Renrui Zhang, Qi Li, Yichen Wu, Renzhen Wang, Xiaojuan Qi, Caifeng Shan, Hongsheng Li, Zhenan Sun,
      <br>
      <i>Preprint.</i>
      <br>
      [<a href="https://github.com/FelixMessi/Awesome-Efficient-dLLMs/blob/main/files/Efficient_dLLMs.pdf">PDF</a>]
      [<a href="https://www.authorea.com/users/1021451/articles/1381451-efficient-diffusion-language-models-a-comprehensive-survey">TechXriv</a>]
      [<a href="https://github.com/FelixMessi/Awesome-Efficient-dLLMs">Github</a>]
      [<a href="https://mp.weixin.qq.com/s/0k_i1YCVrbps3RAPJMMF_w">Synced/机器之心</a>]
      [<a href="#" onclick="showBibSurvey()">bibtex</a>]
      <script>
        function showBibSurvey() {
          const bib = `@article{lin2026efficient,\n
  title={Efficient Diffusion Language Models: A Comprehensive Survey},\n
  author={Lin, Haokun and Jia, Xinle and Liu, Shaozhen and Xia, Shujun and Huang, Weitao and Xu, Haobo and Li, Junyang and Xiao, Yicheng and Xing, Xingrun and Guo, Ziyu and others},\n
  journal={Authorea Preprints},\n
  year={2026}\n
  publisher={Authorea}\n
}`;
          const newWindow = window.open("", "qdlm_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>Image-level Memorization Detection via Inversion-based Inference Perturbation.</b> 
      <br>
      Yue Jiang*, <u>Haokun Lin*</u>, Yang Bai, Bo Peng, Zhili Liu, Yueming Lyu, Yong Yang, Xing Zheng, Jing Dong,
      <br>
      <i>in 13th International Conference on Learning Representations (<b>ICLR 2025</b>)</i>. 
      <br>
      [<a href="https://openreview.net/pdf?id=vwOq7twk7L">PDF</a>]
      [<a href="#" onclick="showBibIIP()">bibtex</a>]
      <script>
        function showBibIIP() {
          const bib = `@@inproceedings{jiang2025image,\n
  title={Image-level Memorization Detection via Inversion-based Inference Perturbation},\n
  author={Jiang, Yue and Lin, Haokun and Bai, Yang and Peng, Bo and Liu, Zhili and Lyu, Yueming and Yang, Yong and Dong, Jing and others},\n
  booktitle={The Thirteenth International Conference on Learning Representations},\n
  year={2025}\n
}`;
          const newWindow = window.open("", "iip_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>QuantVLA: Scale-Calibrated Post-Training Quantization for Vision-Language-Action Models.</b>
      <br>
      Jingxuan Zhang*, Yunta Hsieh*, Zhongwei Wan, <u>Haokun Lin</u>, Xin Wang, Ziqi Wang, Yingtie Lei, Mi Zhang.
      <br>
      <i>in IEEE / CVF Computer Vision and Pattern Recognition Conference 2026 (<b>CVPR 2026</b>)</i>. 
      <br>
      [<a href="https://arxiv.org/pdf/2602.20309">PDF</a>]
      [<a href="https://arxiv.org/abs/2602.20309">arXiv</a>]
      [<a href="https://quantvla.github.io/">Project</a>]
      [<a href="https://github.com/AIoT-MLSys-Lab/QuantVLA">Github</a>]
      [<a href="#" onclick="showBibQuantVLA()">bibtex</a>]
      <script>
        function showBibQuantVLA() {
          const bib = `@zhang2026quantvla,\n
  title={QuantVLA: Scale-Calibrated Post-Training Quantization for Vision-Language-Action Models},\n
  author={Zhang, Jingxuan and Hsieh, Yunta and Wang, Zhongwei and Lin, Haokun and Wang, Xin and Wang, Ziqi and Lei, Yingtie and Zhang, Mi},\n
  journal={arXiv preprint arXiv:2602.20309},\n
  year={2026}\n
}`;
          const newWindow = window.open("", "dogr_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>DOGR: Towards Versatile Visual Document Grounding and Referring.</b>
      <br>
      Yinan Zhou*, Yuxin Chen*, <u>Haokun Lin</u>, Yichen Wu, Shuyu Yang, Zhongang Qi, Chen Ma, Li Zhu, Ying Shan.
      <br>
      <i>in IEEE / CVF International Conference on Computer Vision 2025 (<b>ICCV 2025</b>)</i>. 
      <br>
      [<a href="https://arxiv.org/pdf/2411.17125">PDF</a>]
      [<a href="https://arxiv.org/abs/2411.17125">arXiv</a>]
      <!-- [<a href="https://zyinan99.github.io/">Project</a>] -->
      [<a href="https://github.com/zyinan99/DOGR">Github</a>]
      [<a href="#" onclick="showBibDogr()">bibtex</a>]
      <script>
        function showBibDogr() {
          const bib = `@article{zhou2024dogr,\n
  title={DOGR: Towards versatile visual document grounding and referring},\n
  author={Zhou, Yinan and Chen, Yuxin and Lin, Haokun and Yang, Shuyu and Zhu, Li and Qi, Zhongang and Ma, Chen and Shan, Ying},\n
  journal={arXiv preprint arXiv:2411.17125},\n
  year={2024}\n
}`;
          const newWindow = window.open("", "dogr_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>Scale Up Composed Image Retrieval Learning via Modification Text Generation.</b> 
      <br>
      Yinan Zhou, Yaxiong Wang, <u>Haokun Lin</u>, Chen Ma, Li Zhu, Zhedong Zheng,
      <br>
      <i>in IEEE Transactions on Multimedia (<b>TMM</b>)</i>. 
      <br>
      [<a href="https://openreview.net/pdf?id=vwOq7twk7L">PDF</a>]
      [<a href="https://arxiv.org/abs/2504.05316">arXiv</a>]
      [<a href="#" onclick="showBibscale()">bibtex</a>]
      <script>
        function showBibscale() {
          const bib = `@article{zhou2025scale,\n
  title={Scale Up Composed Image Retrieval Learning via Modification Text Generation},\n
  author={Zhou, Yinan and Wang, Yaxiong and Lin, Haokun and Ma, Chen and Zhu, Li and Zheng, Zhedong},\n
  journal={arXiv preprint arXiv:2504.05316},\n
  year={2025}\n
}`;
          const newWindow = window.open("", "scale_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>MATHVERSE: Does Your Multi-modal LLM Truly See the Diagrams in Visual Math Problems?</b> 
      <br>
      Renrui Zhang*, Dongzhi Jiang*, Yichi Zhang*, <u>Haokun Lin</u>, Ziyu Guo, Pengshuo Qiu, Aojun Zhou, Pan Lu, Kai-Wei Chang, Peng Gao, Hongsheng Li,
      <br>
      <i>in 18th European Conference on Computer Vision (<b>ECCV 2024</b>)</i>. 
      <br>
      [<a href="https://arxiv.org/pdf/2403.14624">PDF</a>]
      [<a href="https://arxiv.org/abs/2403.14624">arXiv</a>]
      [<a href="https://mathverse-cuhk.github.io/">Project</a>]
      [<a href="https://github.com/ZrrSkywalker/MathVerse">Github</a>]
      [<a href="https://huggingface.co/datasets/AI4Math/MathVerse">Dataset</a>]
      [<a href="https://mp.weixin.qq.com/s/gEcCi92PdMMCItFII84lcw">Synced/机器之心</a>] 
      [<a href="#" onclick="showBibmath()">bibtex</a>]
      <script>
        function showBibmath() {
          const bib = `@inproceedings{zhang2024mathverse,\n
  title={Mathverse: Does your multi-modal llm truly see the diagrams in visual math problems?},\n
  author={Zhang, Renrui and Jiang, Dongzhi and Zhang, Yichi and Lin, Haokun and Guo, Ziyu and Qiu, Pengshuo and Zhou, Aojun and Lu, Pan and Chang, Kai-Wei and Qiao, Yu and others},\n
  booktitle={European Conference on Computer Vision},\n
  pages={169--186},\n
  year={2024},\n
  organization={Springer}\n
}`;
          const newWindow = window.open("", "mathverse_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>Plug-and-Play: An Efficient Post-training Pruning Method for Large Language Models.</b> 
      <br>
      Yingtao Zhang, Haoli Bai, <u>Haokun Lin</u>, Jialin Zhao, Lu Hou, Carlo Vittorio Cannistraci,
      <br>
      <i>in 12th International Conference on Learning Representations (<b>ICLR 2024</b>)</i>. 
      <br>
      [<a href="https://openreview.net/pdf?id=Tr0lPx9woF">PDF</a>]
      [<a href="https://openreview.net/forum?id=Tr0lPx9woF">OpenReview</a>]
      [<a href="https://github.com/biomedical-cybernetics/Relative-importance-and-activation-pruning">Github</a>]
      [<a href="#" onclick="showBibRIA()">bibtex</a>]
      <script>
        function showBibRIA() {
          const bib = `@inproceedings{zhangplug,\n
  title={Plug-and-Play: An Efficient Post-training Pruning Method for Large Language Models},\n
  author={Zhang, Yingtao and Bai, Haoli and Lin, Haokun and Zhao, Jialin and Hou, Lu and Cannistraci, Carlo Vittorio},\n
  booktitle={The Twelfth International Conference on Learning Representations}\n
}`;
          const newWindow = window.open("", "plug_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>IntactKV: Improving Large Language Model Quantization by Keeping Pivot Tokens Intact.</b>
      <br>
      Ruikang Liu, Haoli Bai, <u>Haokun Lin</u>, Yuening Li, Han Gao, Zhengzhuo Xu, Lu Hou, Jun Yao, Chun Yuan,
      <br>
      <i>in Findings of 62nd Annual Meeting of the Association for Computational Linguistics (<b>ACL 2024 Findings</b>)</i>
      <br>
      [<a href="https://arxiv.org/pdf/2403.01241">PDF</a>]
      [<a href="https://arxiv.org/abs/2403.01241">arXiv</a>]
      [<a href="https://github.com/ruikangliu/IntactKV">Github</a>]
      [<a href="#" onclick="showBibintact()">bibtex</a>]
      <script>
        function showBibintact() {
          const bib = `@article{liu2024intactkv,\n
  title={Intactkv: Improving large language model quantization by keeping pivot tokens intact},\n
  author={Liu, Ruikang and Bai, Haoli and Lin, Haokun and Li, Yuening and Gao, Han and Xu, Zhengzhuo and Hou, Lu and Yao, Jun and Yuan, Chun},\n
  journal={arXiv preprint arXiv:2403.01241},\n
  year={2024}\n
}`;
          const newWindow = window.open("", "intactkv_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
       <b>MedREK: Retrieval-Based Editing for Medical LLMs with Key-Aware Prompts.
       </b> 
      <br>
      Shujun Xia*, <u>Haokun Lin#*</u>, Yichen Wu^, Yinan Zhou, Zixuan Li, Zhongwei Wan, Xingrun Xing, Yefeng Zheng, Xiang Li, Caifeng Shan, Zhenan Sun, Quanzheng Li^,
      <br>
      <i>in ResponsibleFM @ NeurIPS 2025.</i>
      <br>
      [<a href="https://arxiv.org/pdf/2510.13500">PDF</a>]
      [<a href="https://arxiv.org/abs/2510.13500">arXiv</a>]
      [<a href="https://github.com/mylittleriver/MedREK">Github</a>]
      <!-- [<a href="https://huggingface.co/TencentARC/TokLIP">HuggingFace</a>] -->
      [<a href="#" onclick="showBibMedRek()">bibtex</a>]
      <script>
        function showBibMedRek() {
          const bib = `@article{xia2025medrek,\n
  title={MedREK: Retrieval-Based Editing for Medical LLMs with Key-Aware Prompts},\n
  author={Xia, Shujun and Lin, Haokun and Wu, Yichen and Zhou, Yinan and Li, Zixuan and Wan, Zhongwei and Xing, Xingrun and Zheng, Yefeng and Li, Xiang and Shan, Caifeng and others},\n
  journal={arXiv preprint arXiv:2510.13500},\n
  year={2025}\n
}`;
          const newWindow = window.open("", "medrek_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>LRQ-DiT: Log-Rotation Post-Training Quantization of Diffusion Transformers for Text-to-Image Generation.</b>
      <br>
      Lianwei Yang*, <u>Haokun Lin*</u>, Tianchen Zhao*, Yichen Wu, Hongyu Zhu, Ruiqi Xie, Zhenan Sun, Yu Wang, Qingyi Gu,
      <br>
      <i>Preprint.</i>
      <br>
      [<a href="https://arxiv.org/pdf/2508.03485">PDF</a>]
      [<a href="https://arxiv.org/abs/2508.03485">arXiv</a>]
      [<a href="https://github.com/yanglianwei/LRQ-DiT">Github</a>]
      [<a href="#" onclick="showBibLrq()">bibtex</a>]
      <script>
        function showBibLrq() {
          const bib = `@article{yang2025lrq,\n
  title={LRQ-DiT: Log-Rotation Post-Training Quantization of Diffusion Transformers for Text-to-Image Generation},\n
  author={Yang, Lianwei and Lin, Haokun and Zhao, Tianchen and Wu, Yichen and Zhu, Hongyu and Xie, Ruiqi and Sun, Zhenan and Wang, Yu and Gu, Qingyi},\n
  journal={arXiv preprint arXiv:2508.03485},\n
  year={2025}\n
}`;
          const newWindow = window.open("", "lrq_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>


  <tr>
    <td style="padding:5px;width:70%;vertical-align:middle;border-right:none;border-bottom:none;">
      <b>DopQ-ViT: Towards Distribution-Friendly and Outlier-Aware Post-Training Quantization for Vision Transformers.</b>
      <br>
      Lianwei Yang*, Haisong Gong*, <u>Haokun Lin*</u>, Yichen Wu, Zhenan Sun, Liang Wang, Qingyi Gu,
      <br>
      <i>Preprint.</i>
      <br>
      [<a href="https://arxiv.org/pdf/2408.03291">PDF</a>]
      [<a href="https://arxiv.org/abs/2408.03291">arXiv</a>]
      <!-- [<a href="https://github.com/TencentARC/TokLIP">Github</a>]
      [<a href="https://huggingface.co/TencentARC/TokLIP">HuggingFace</a>] -->
      [<a href="#" onclick="showBibDopq()">bibtex</a>]
      <script>
        function showBibDopq() {
          const bib = `@article{yang2024dopq,\n
  title={DopQ-ViT: Towards Distribution-Friendly and Outlier-Aware Post-Training Quantization for Vision Transformers},\n
  author={Yang, Lianwei and Gong, Haisong and Lin, Haokun and Wu, Yichen and Sun, Zhenan and Gu, Qingyi},\n
  journal={arXiv preprint arXiv:2408.03291},\n
  year={2024}\n
}`;
          const newWindow = window.open("", "dopq_bibtex");
          newWindow.document.write("<pre style='font-family: monospace; padding: 20px;'>" + bib + "</pre>");
        }
      </script>
    </td>
    <!-- <td style="padding:10px;width:30%;vertical-align:middle;border-right:none;border-bottom:none;">
      <a href="/images/.png">
      <img src='/images/.png' width="300">
      </a>
    </td> -->
  </tr>

</table>