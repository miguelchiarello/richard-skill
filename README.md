# Revisão de onboarding e landing

Esta pasta guarda uma skill para qualquer agente. Ela revisa landing pages e fluxos de onboarding com o método ensinado por Richard Designer. O arquivo da skill é `SKILL.md`, com o id `revisao-onboarding-landing`. Quando roda, ela entrega uma revisão priorizada na ordem conversão → ativação → retenção, e marca como **Inferência** tudo o que Richard não disse.

A fonte é a palestra “Os erros do seu Onboarding — com Richard Designer”, dada na comunidade biip (biip.club). O site dele é [thesupertape.com](https://www.thesupertape.com/), e o X é [@richardrx](https://x.com/richardrx). A gravação é de 5 de novembro de 2026, marcada como sessão de convidado daquela quinta-feira, e dura cerca de 1 hora e 47 minutos. O id da gravação é `rec_4c9bfa88359f43`.

A aba “Transcrição” do próprio biip.club só tinha trechos curtos em destaque, não a palestra inteira. O vídeo foi baixado da página de gravação exclusiva para membros e transcrito localmente com o faster-whisper (modelo `small`, idioma `pt`). A transcrição tem 2.783 segmentos e cobre de 00:00 a 1:47:08.

Essa transcrição completa foi passada ao Claude no claude.ai (Opus 5.5, High), na conta do Miguel, com a instrução de destilar um `SKILL.md` reutilizável e de marcar as inferências. O Claude produziu esta skill a partir dessa transcrição.

A gravação bruta e a transcrição completa não estão neste repositório. Elas vêm de uma sessão exclusiva para membros da comunidade e não devem ser republicadas.

Para usar, carregue ou anexe o `SKILL.md` em qualquer agente, ou peça que rode a skill `revisao-onboarding-landing` ao revisar uma landing page ou um fluxo de onboarding.
