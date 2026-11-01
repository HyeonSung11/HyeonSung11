![header](https://capsule-render.vercel.app/api?type=waving&height=200&text=Welcome+to+HyeonSung11's+GitHub!👋&fontAlign=50&fontAlignY=40&color=gradient&fontSize=40)

<div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;">About Me</h2>
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;">
        🎓About:<br>
        - M.S. student, Graduate School of Automotive Engineering, Seoul National University of Science and Technology (SeoulTech).<br>
        - Advisor: Prof. Jong-Eun Ha.<br><br>
        🔥Current:<br>
        - Researching VLM / VLA-based robotic planning and manipulation.<br>
        - Injecting knowledge from frozen foundation models (metric depth, CLIP, DINOv2/DINOv3, Grounding DINO) into robot perception, planning, and action models without changing their inference path.<br>
        - Making VLA fine-tuning and visual reasoning RL work on a two-GPU workstation (2 × RTX 4090) instead of a datacenter cluster.<br><br>
        🎯Future:<br>
        - World-action models (WAMs): unifying visual world prediction and action generation in one model, and learning latent dynamics from human videos as a pretraining signal for robot policies.<br>
        - Resource-efficient learning for robot spatial perception, planning, and action models.<br><br>
        ⭐Keywords:<br>
        - Vision-Language Models, Vision-Language-Action, Reinforcement Learning for Visual Reasoning, World Models, 3D Gaussian Splatting, Robotic Manipulation, Depth Estimation, Resource-Efficient Training.<br>
    </div>
</div>

<br>

## 📄 Publications

| Year | Paper | Venue | Code |
|---|---|---|---|
| 2026 | **ReflectVLM+: Enhancing VLM-based Robotic Planning via Quantitative Stagnation Detection and Trajectory Refinement** | *International Journal of Precision Engineering and Manufacturing* (SCIE) · [DOI](https://doi.org/10.1007/s12541-026-01548-y) | [ReflectVLM-Plus](https://github.com/HyeonSung11/ReflectVLM-Plus) |
| 2026 | **Geometry-guided 3D Gaussian Splatting** (기하 정보 기반 3D Gaussian Splatting) | *Journal of Institute of Control, Robotics and Systems*, 32(8) · [DOI](https://doi.org/10.5302/J.ICROS.2026.26.0108) | [Geometry-Guided-3DGS](https://github.com/HyeonSung11/Geometry-Guided-3DGS) |

<br>
## 🧪 Research Code (manuscripts in preparation)

| Year | Paper | Summary | Code |
|---|---|---|---|
| 2026 | **Design and Analysis of Visual Self-Attention and State Towers for a Lightweight Vision-Language-Action Model** (경량 비전-언어-행동 모델을 위한 시각 셀프 어텐션 타워와 상태 타워의 설계 및 분석) | Adds a gated visual self-attention tower, partially co-initialized from the Grounding DINO feature enhancer, and an asymmetric state tower to the LLM-free TurboVLA; five configurations compared on LIBERO and RoboTwin 2.0 with a seed-variation analysis. Built on [TurboVLA](https://github.com/H-EmbodVis/TurboVLA). | [TurboVLA-Vision-State-Towers](https://github.com/HyeonSung11/TurboVLA-Vision-State-Towers) |
| 2026 | **Resource-Efficient Fine-Tuning of Vision-Language-Action Models by Replacing the Pixel World Model with Latent Feature Regression** (픽셀 세계모델을 잠재 특징 회귀로 대체한 비전-언어-행동 모델의 자원 효율적 미세조정) | Replaces the 5B frozen video-diffusion world-model loss of InternVLA-A1.5 with regression to frozen DINOv2 features of the future frame, cutting training memory while keeping the inference path unchanged. Built on [InternVLA-A1.5](https://github.com/InternRobotics/InternVLA-A-series). | [InternVLA-Latent-Foresight](https://github.com/HyeonSung11/InternVLA-Latent-Foresight) |
| 2026 | **Visual Reasoning RL under Limited Resources: Difficulty-Aware Online Curriculum and Format-Level Reward Hacking** (제한된 자원 환경에서의 시각 추론 강화학습: 난이도 인지 온라인 커리큘럼과 형식 수준 보상 해킹 분석) | Runs an open visual-reasoning RL recipe (GSPO, Qwen3-VL-8B with LoRA) on 2 × RTX 4090 with a p(1 − p) difficulty-aware online curriculum, and analyzes format-level reward hacking under a small rollout budget. Built on [Vero](https://github.com/zlab-princeton/vero). | [Difficulty-Aware-Visual-RL](https://github.com/HyeonSung11/Difficulty-Aware-Visual-RL) |

<br>
