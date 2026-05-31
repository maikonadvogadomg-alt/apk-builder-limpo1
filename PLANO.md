# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 31/05/2026, 17:23:43
> **190 arquivo(s)** | **~13.526 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Site/Pagina Web (HTML/CSS/JS)
- **Frontend / Stack principal:** HTML + CSS + JavaScript

**Para rodar o projeto:**
```bash
# Abra index.html no Preview (botao Play)
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── assets/
│   ├── www/
│   │   ├── assets/
│   │   │   ├── index-BJuPNGJb.css
│   │   │   ├── Terminal-cLUd5btK.js
│   │   │   └── Terminal-G5OQeJvU.css
│   │   ├── favicon.svg
│   │   ├── icon-192.svg
│   │   ├── icon-512.svg
│   │   ├── index.html
│   │   ├── manifest.json
│   │   └── sw.js
│   └── app.config
├── META-INF/
│   ├── services/
│   │   ├── kotlin.reflect.jvm.internal.impl.builtins.BuiltInsLoader
│   │   ├── kotlin.reflect.jvm.internal.impl.resolve.ExternalOverridabilityCondition
│   │   ├── kotlinx.coroutines.CoroutineExceptionHandler
│   │   └── kotlinx.coroutines.internal.MainDispatcherFactory
│   ├── androidx.activity_activity.version
│   ├── androidx.annotation_annotation-experimental.version
│   ├── androidx.appcompat_appcompat-resources.version
│   ├── androidx.appcompat_appcompat.version
│   ├── androidx.arch.core_core-runtime.version
│   ├── androidx.asynclayoutinflater_asynclayoutinflater.version
│   ├── androidx.autofill_autofill.version
│   ├── androidx.coordinatorlayout_coordinatorlayout.version
│   ├── androidx.core_core-ktx.version
│   ├── androidx.core_core.version
│   ├── androidx.cursoradapter_cursoradapter.version
│   ├── androidx.customview_customview.version
│   ├── androidx.documentfile_documentfile.version
│   ├── androidx.drawerlayout_drawerlayout.version
│   ├── androidx.emoji2_emoji2-views-helper.version
│   ├── androidx.emoji2_emoji2.version
│   ├── androidx.fragment_fragment.version
│   ├── androidx.interpolator_interpolator.version
│   ├── androidx.legacy_legacy-support-core-ui.version
│   ├── androidx.legacy_legacy-support-core-utils.version
│   ├── androidx.legacy_legacy-support-v4.version
│   ├── androidx.lifecycle_lifecycle-livedata-core.version
│   ├── androidx.lifecycle_lifecycle-livedata.version
│   ├── androidx.lifecycle_lifecycle-process.version
│   ├── androidx.lifecycle_lifecycle-runtime.version
│   ├── androidx.lifecycle_lifecycle-viewmodel-savedstate.version
│   ├── androidx.lifecycle_lifecycle-viewmodel.version
│   ├── androidx.loader_loader.version
│   ├── androidx.localbroadcastmanager_localbroadcastmanager.version
│   ├── androidx.media_media.version
│   ├── androidx.print_print.version
│   ├── androidx.savedstate_savedstate.version
│   ├── androidx.slidingpanelayout_slidingpanelayout.version
│   ├── androidx.startup_startup-runtime.version
│   ├── androidx.swiperefreshlayout_swiperefreshlayout.version
│   ├── androidx.tracing_tracing-ktx.version
│   ├── androidx.tracing_tracing.version
│   ├── androidx.vectordrawable_vectordrawable-animated.version
│   ├── androidx.vectordrawable_vectordrawable.version
│   ├── androidx.versionedparcelable_versionedparcelable.version
│   ├── androidx.viewpager_viewpager.version
│   ├── androidx.webkit_webkit.version
│   ├── CERT.SF
│   ├── kotlinx_coroutines_android.version
│   ├── kotlinx_coroutines_core.version
│   └── MANIFEST.MF
├── okhttp3/
│   └── internal/
│       └── publicsuffix/
│           └── NOTICE
├── org/
│   └── apache/
│       └── commons/
│           └── codec/
│               └── language/
│                   ├── bm/
│                   │   ├── ash_approx_any.txt
│                   │   ├── ash_approx_common.txt
│                   │   ├── ash_approx_cyrillic.txt
│                   │   ├── ash_approx_english.txt
│                   │   ├── ash_approx_french.txt
│                   │   ├── ash_approx_german.txt
│                   │   ├── ash_approx_hebrew.txt
│                   │   ├── ash_approx_hungarian.txt
│                   │   ├── ash_approx_polish.txt
│                   │   ├── ash_approx_romanian.txt
│                   │   ├── ash_approx_russian.txt
│                   │   ├── ash_approx_spanish.txt
│                   │   ├── ash_exact_any.txt
│                   │   ├── ash_exact_approx_common.txt
│                   │   ├── ash_exact_common.txt
│                   │   ├── ash_exact_cyrillic.txt
│                   │   ├── ash_exact_english.txt
│                   │   ├── ash_exact_french.txt
│                   │   ├── ash_exact_german.txt
│                   │   ├── ash_exact_hebrew.txt
│                   │   ├── ash_exact_hungarian.txt
│                   │   ├── ash_exact_polish.txt
│                   │   ├── ash_exact_romanian.txt
│                   │   ├── ash_exact_russian.txt
│                   │   ├── ash_exact_spanish.txt
│                   │   ├── ash_hebrew_common.txt
│                   │   ├── ash_lang.txt
│                   │   ├── ash_languages.txt
│                   │   ├── ash_rules_any.txt
│                   │   ├── ash_rules_cyrillic.txt
│                   │   ├── ash_rules_english.txt
│                   │   ├── ash_rules_french.txt
│                   │   ├── ash_rules_german.txt
│                   │   ├── ash_rules_hebrew.txt
│                   │   ├── ash_rules_hungarian.txt
│                   │   ├── ash_rules_polish.txt
│                   │   ├── ash_rules_romanian.txt
│                   │   ├── ash_rules_russian.txt
│                   │   ├── ash_rules_spanish.txt
│                   │   ├── gen_approx_any.txt
│                   │   ├── gen_approx_arabic.txt
│                   │   ├── gen_approx_common.txt
│                   │   ├── gen_approx_cyrillic.txt
│                   │   ├── gen_approx_czech.txt
│                   │   ├── gen_approx_dutch.txt
│                   │   ├── gen_approx_english.txt
│                   │   ├── gen_approx_french.txt
│                   │   ├── gen_approx_german.txt
│                   │   ├── gen_approx_greek.txt
│                   │   ├── gen_approx_greeklatin.txt
│                   │   ├── gen_approx_hebrew.txt
│                   │   ├── gen_approx_hungarian.txt
│                   │   ├── gen_approx_italian.txt
│                   │   ├── gen_approx_polish.txt
│                   │   ├── gen_approx_portuguese.txt
│                   │   ├── gen_approx_romanian.txt
│                   │   ├── gen_approx_russian.txt
│                   │   ├── gen_approx_spanish.txt
│                   │   ├── gen_approx_turkish.txt
│                   │   ├── gen_exact_any.txt
│                   │   ├── gen_exact_approx_common.txt
│                   │   ├── gen_exact_arabic.txt
│                   │   ├── gen_exact_common.txt
│                   │   ├── gen_exact_cyrillic.txt
│                   │   ├── gen_exact_czech.txt
│                   │   ├── gen_exact_dutch.txt
│                   │   ├── gen_exact_english.txt
│                   │   ├── gen_exact_french.txt
│                   │   ├── gen_exact_german.txt
│                   │   ├── gen_exact_greek.txt
│                   │   ├── gen_exact_greeklatin.txt
│                   │   ├── gen_exact_hebrew.txt
│                   │   ├── gen_exact_hungarian.txt
│                   │   ├── gen_exact_italian.txt
│                   │   ├── gen_exact_polish.txt
│                   │   ├── gen_exact_portuguese.txt
│                   │   ├── gen_exact_romanian.txt
│                   │   ├── gen_exact_russian.txt
│                   │   ├── gen_exact_spanish.txt
│                   │   ├── gen_exact_turkish.txt
│                   │   ├── gen_hebrew_common.txt
│                   │   ├── gen_lang.txt
│                   │   ├── gen_languages.txt
│                   │   ├── gen_rules_any.txt
│                   │   ├── gen_rules_arabic.txt
│                   │   ├── gen_rules_cyrillic.txt
│                   │   ├── gen_rules_czech.txt
│                   │   ├── gen_rules_dutch.txt
│                   │   ├── gen_rules_english.txt
│                   │   ├── gen_rules_french.txt
│                   │   ├── gen_rules_german.txt
│                   │   ├── gen_rules_greek.txt
│                   │   ├── gen_rules_greeklatin.txt
│                   │   ├── gen_rules_hebrew.txt
│                   │   ├── gen_rules_hungarian.txt
│                   │   ├── gen_rules_italian.txt
│                   │   ├── gen_rules_polish.txt
│                   │   ├── gen_rules_portuguese.txt
│                   │   ├── gen_rules_romanian.txt
│                   │   ├── gen_rules_russian.txt
│                   │   ├── gen_rules_spanish.txt
│                   │   ├── gen_rules_turkish.txt
│                   │   ├── lang.txt
│                   │   ├── sep_approx_any.txt
│                   │   ├── sep_approx_common.txt
│                   │   ├── sep_approx_french.txt
│                   │   ├── sep_approx_hebrew.txt
│                   │   ├── sep_approx_italian.txt
│                   │   ├── sep_approx_portuguese.txt
│                   │   ├── sep_approx_spanish.txt
│                   │   ├── sep_exact_any.txt
│                   │   ├── sep_exact_approx_common.txt
│                   │   ├── sep_exact_common.txt
│                   │   ├── sep_exact_french.txt
│                   │   ├── sep_exact_hebrew.txt
│                   │   ├── sep_exact_italian.txt
│                   │   ├── sep_exact_portuguese.txt
│                   │   ├── sep_exact_spanish.txt
│                   │   ├── sep_hebrew_common.txt
│                   │   ├── sep_lang.txt
│                   │   ├── sep_languages.txt
│                   │   ├── sep_rules_any.txt
│                   │   ├── sep_rules_french.txt
│                   │   ├── sep_rules_hebrew.txt
│                   │   ├── sep_rules_italian.txt
│                   │   ├── sep_rules_portuguese.txt
│                   │   └── sep_rules_spanish.txt
│                   └── dmrules.txt
└── kotlin-tooling-metadata.json
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** HTML + CSS + JavaScript

---

## ARQUIVOS PRINCIPAIS

- `assets/www/index.html` — Arquivo principal

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`kotlin-tooling-metadata.json`** _(24 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`app.config`** _(1 linha)_
Arquivo CONFIG — parte do projeto.

---

### 📁 `META-INF/`
> Pasta 'META-INF' — agrupamento de arquivos relacionados.

**`CERT.SF`** _(2437 linhas)_
Arquivo SF — parte do projeto.

**`MANIFEST.MF`** _(2436 linhas)_
Arquivo MF — parte do projeto.

**`androidx.activity_activity.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.annotation_annotation-experimental.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.appcompat_appcompat-resources.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.appcompat_appcompat.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.arch.core_core-runtime.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.asynclayoutinflater_asynclayoutinflater.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.autofill_autofill.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.coordinatorlayout_coordinatorlayout.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.core_core-ktx.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.core_core.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.cursoradapter_cursoradapter.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.customview_customview.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.documentfile_documentfile.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.drawerlayout_drawerlayout.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.emoji2_emoji2-views-helper.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.emoji2_emoji2.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.fragment_fragment.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.interpolator_interpolator.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.legacy_legacy-support-core-ui.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.legacy_legacy-support-core-utils.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.legacy_legacy-support-v4.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.lifecycle_lifecycle-livedata-core.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.lifecycle_lifecycle-livedata.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.lifecycle_lifecycle-process.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.lifecycle_lifecycle-runtime.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.lifecycle_lifecycle-viewmodel-savedstate.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.lifecycle_lifecycle-viewmodel.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.loader_loader.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.localbroadcastmanager_localbroadcastmanager.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.media_media.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.print_print.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.savedstate_savedstate.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.slidingpanelayout_slidingpanelayout.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.startup_startup-runtime.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.swiperefreshlayout_swiperefreshlayout.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.tracing_tracing-ktx.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.tracing_tracing.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.vectordrawable_vectordrawable-animated.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.vectordrawable_vectordrawable.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.versionedparcelable_versionedparcelable.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.viewpager_viewpager.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`androidx.webkit_webkit.version`** _(2 linhas)_
Arquivo VERSION — parte do projeto.

**`kotlinx_coroutines_android.version`** _(1 linha)_
Arquivo VERSION — parte do projeto.

**`kotlinx_coroutines_core.version`** _(1 linha)_
Arquivo VERSION — parte do projeto.

---

### 📁 `assets/www/`
> Pasta 'www' — agrupamento de arquivos relacionados.

**`favicon.svg`** _(4 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.svg`** _(12 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-512.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`index.html`** _(41 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(45 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`sw.js`** _(71 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `META-INF/services/`
> Comunicacao com servidor, banco de dados ou APIs externas.

**`kotlin.reflect.jvm.internal.impl.builtins.BuiltInsLoader`** _(1 linha)_
Arquivo BUILTINSLOADER — parte do projeto.

**`kotlin.reflect.jvm.internal.impl.resolve.ExternalOverridabilityCondition`** _(3 linhas)_
Arquivo EXTERNALOVERRIDABILITYCONDITION — parte do projeto.

**`kotlinx.coroutines.CoroutineExceptionHandler`** _(2 linhas)_
Arquivo COROUTINEEXCEPTIONHANDLER — parte do projeto.

**`kotlinx.coroutines.internal.MainDispatcherFactory`** _(2 linhas)_
Arquivo MAINDISPATCHERFACTORY — parte do projeto.

---

### 📁 `assets/www/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`Terminal-G5OQeJvU.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`Terminal-cLUd5btK.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index-BJuPNGJb.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

---

### 📁 `okhttp3/internal/publicsuffix/`
> Pasta 'publicsuffix' — agrupamento de arquivos relacionados.

**`NOTICE`** _(6 linhas)_
Arquivo NOTICE — parte do projeto.

---

### 📁 `org/apache/commons/codec/language/`
> Pasta 'language' — agrupamento de arquivos relacionados.

**`dmrules.txt`** _(201 linhas)_
Arquivo TXT — parte do projeto.

---

### 📁 `org/apache/commons/codec/language/bm/`
> Pasta 'bm' — agrupamento de arquivos relacionados.

**`ash_approx_any.txt`** _(156 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_common.txt`** _(225 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_cyrillic.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_english.txt`** _(48 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_french.txt`** _(40 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_german.txt`** _(73 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_hebrew.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_hungarian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_polish.txt`** _(84 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_romanian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_russian.txt`** _(48 linhas)_
Arquivo TXT — parte do projeto.

**`ash_approx_spanish.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_any.txt`** _(53 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_approx_common.txt`** _(82 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_common.txt`** _(34 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_cyrillic.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_english.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_french.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_german.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_hebrew.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_hungarian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_polish.txt`** _(24 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_romanian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_russian.txt`** _(19 linhas)_
Arquivo TXT — parte do projeto.

**`ash_exact_spanish.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`ash_hebrew_common.txt`** _(124 linhas)_
Arquivo TXT — parte do projeto.

**`ash_lang.txt`** _(207 linhas)_
Arquivo TXT — parte do projeto.

**`ash_languages.txt`** _(29 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_any.txt`** _(333 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_cyrillic.txt`** _(101 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_english.txt`** _(108 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_french.txt`** _(92 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_german.txt`** _(129 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_hebrew.txt`** _(63 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_hungarian.txt`** _(85 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_polish.txt`** _(186 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_romanian.txt`** _(67 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_russian.txt`** _(165 linhas)_
Arquivo TXT — parte do projeto.

**`ash_rules_spanish.txt`** _(78 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_any.txt`** _(132 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_arabic.txt`** _(27 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_common.txt`** _(234 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_cyrillic.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_czech.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_dutch.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_english.txt`** _(48 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_french.txt`** _(26 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_german.txt`** _(74 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_greek.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_greeklatin.txt`** _(21 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_hebrew.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_hungarian.txt`** _(19 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_italian.txt`** _(19 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_polish.txt`** _(85 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_portuguese.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_romanian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_russian.txt`** _(49 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_spanish.txt`** _(22 linhas)_
Arquivo TXT — parte do projeto.

**`gen_approx_turkish.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_any.txt`** _(41 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_approx_common.txt`** _(80 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_arabic.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_common.txt`** _(33 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_cyrillic.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_czech.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_dutch.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_english.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_french.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_german.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_greek.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_greeklatin.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_hebrew.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_hungarian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_italian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_polish.txt`** _(23 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_portuguese.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_romanian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_russian.txt`** _(19 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_spanish.txt`** _(20 linhas)_
Arquivo TXT — parte do projeto.

**`gen_exact_turkish.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`gen_hebrew_common.txt`** _(113 linhas)_
Arquivo TXT — parte do projeto.

**`gen_lang.txt`** _(296 linhas)_
Arquivo TXT — parte do projeto.

**`gen_languages.txt`** _(37 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_any.txt`** _(368 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_arabic.txt`** _(77 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_cyrillic.txt`** _(100 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_czech.txt`** _(68 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_dutch.txt`** _(79 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_english.txt`** _(114 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_french.txt`** _(115 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_german.txt`** _(130 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_greek.txt`** _(98 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_greeklatin.txt`** _(119 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_hebrew.txt`** _(63 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_hungarian.txt`** _(84 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_italian.txt`** _(78 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_polish.txt`** _(186 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_portuguese.txt`** _(106 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_romanian.txt`** _(65 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_russian.txt`** _(143 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_spanish.txt`** _(86 linhas)_
Arquivo TXT — parte do projeto.

**`gen_rules_turkish.txt`** _(51 linhas)_
Arquivo TXT — parte do projeto.

**`lang.txt`** _(17 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_any.txt`** _(20 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_common.txt`** _(116 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_french.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_hebrew.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_italian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_portuguese.txt`** _(19 linhas)_
Arquivo TXT — parte do projeto.

**`sep_approx_spanish.txt`** _(19 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_any.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_approx_common.txt`** _(80 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_common.txt`** _(33 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_french.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_hebrew.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_italian.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_portuguese.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_exact_spanish.txt`** _(18 linhas)_
Arquivo TXT — parte do projeto.

**`sep_hebrew_common.txt`** _(87 linhas)_
Arquivo TXT — parte do projeto.

**`sep_lang.txt`** _(106 linhas)_
Arquivo TXT — parte do projeto.

**`sep_languages.txt`** _(24 linhas)_
Arquivo TXT — parte do projeto.

**`sep_rules_any.txt`** _(156 linhas)_
Arquivo TXT — parte do projeto.

**`sep_rules_french.txt`** _(92 linhas)_
Arquivo TXT — parte do projeto.

**`sep_rules_hebrew.txt`** _(63 linhas)_
Arquivo TXT — parte do projeto.

**`sep_rules_italian.txt`** _(77 linhas)_
Arquivo TXT — parte do projeto.

**`sep_rules_portuguese.txt`** _(105 linhas)_
Arquivo TXT — parte do projeto.

**`sep_rules_spanish.txt`** _(96 linhas)_
Arquivo TXT — parte do projeto.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Site/Pagina Web (HTML/CSS/JS)
Stack: HTML + CSS + JavaScript
Arquivos: 190 | Linhas: ~13.526

Estrutura principal:
  META-INF/CERT.SF
  META-INF/MANIFEST.MF
  META-INF/androidx.activity_activity.version
  META-INF/androidx.annotation_annotation-experimental.version
  META-INF/androidx.appcompat_appcompat-resources.version
  META-INF/androidx.appcompat_appcompat.version
  META-INF/androidx.arch.core_core-runtime.version
  META-INF/androidx.asynclayoutinflater_asynclayoutinflater.version
  META-INF/androidx.autofill_autofill.version
  META-INF/androidx.coordinatorlayout_coordinatorlayout.version
  META-INF/androidx.core_core-ktx.version
  META-INF/androidx.core_core.version
  META-INF/androidx.cursoradapter_cursoradapter.version
  META-INF/androidx.customview_customview.version
  META-INF/androidx.documentfile_documentfile.version
  META-INF/androidx.drawerlayout_drawerlayout.version
  META-INF/androidx.emoji2_emoji2-views-helper.version
  META-INF/androidx.emoji2_emoji2.version
  META-INF/androidx.fragment_fragment.version
  META-INF/androidx.interpolator_interpolator.version
  META-INF/androidx.legacy_legacy-support-core-ui.version
  META-INF/androidx.legacy_legacy-support-core-utils.version
  META-INF/androidx.legacy_legacy-support-v4.version
  META-INF/androidx.lifecycle_lifecycle-livedata-core.version
  META-INF/androidx.lifecycle_lifecycle-livedata.version
  META-INF/androidx.lifecycle_lifecycle-process.version
  META-INF/androidx.lifecycle_lifecycle-runtime.version
  META-INF/androidx.lifecycle_lifecycle-viewmodel-savedstate.version
  META-INF/androidx.lifecycle_lifecycle-viewmodel.version
  META-INF/androidx.loader_loader.version
  META-INF/androidx.localbroadcastmanager_localbroadcastmanager.version
  META-INF/androidx.media_media.version
  META-INF/androidx.print_print.version
  META-INF/androidx.savedstate_savedstate.version
  META-INF/androidx.slidingpanelayout_slidingpanelayout.version
  META-INF/androidx.startup_startup-runtime.version
  META-INF/androidx.swiperefreshlayout_swiperefreshlayout.version
  META-INF/androidx.tracing_tracing-ktx.version
  META-INF/androidx.tracing_tracing.version
  META-INF/androidx.vectordrawable_vectordrawable-animated.version
  META-INF/androidx.vectordrawable_vectordrawable.version
  META-INF/androidx.versionedparcelable_versionedparcelable.version
  META-INF/androidx.viewpager_viewpager.version
  META-INF/androidx.webkit_webkit.version
  META-INF/kotlinx_coroutines_android.version
  META-INF/kotlinx_coroutines_core.version
  META-INF/services/kotlin.reflect.jvm.internal.impl.builtins.BuiltInsLoader
  META-INF/services/kotlin.reflect.jvm.internal.impl.resolve.ExternalOverridabilityCondition
  META-INF/services/kotlinx.coroutines.CoroutineExceptionHandler
  META-INF/services/kotlinx.coroutines.internal.MainDispatcherFactory
  assets/app.config
  assets/www/assets/Terminal-G5OQeJvU.css
  assets/www/assets/Terminal-cLUd5btK.js
  assets/www/assets/index-BJuPNGJb.css
  assets/www/favicon.svg
  assets/www/icon-192.svg
  assets/www/icon-512.svg
  assets/www/index.html
  assets/www/manifest.json
  assets/www/sw.js
  kotlin-tooling-metadata.json
  okhttp3/internal/publicsuffix/NOTICE
  org/apache/commons/codec/language/bm/ash_approx_any.txt
  org/apache/commons/codec/language/bm/ash_approx_common.txt
  org/apache/commons/codec/language/bm/ash_approx_cyrillic.txt
  org/apache/commons/codec/language/bm/ash_approx_english.txt
  org/apache/commons/codec/language/bm/ash_approx_french.txt
  org/apache/commons/codec/language/bm/ash_approx_german.txt
  org/apache/commons/codec/language/bm/ash_approx_hebrew.txt
  org/apache/commons/codec/language/bm/ash_approx_hungarian.txt
  org/apache/commons/codec/language/bm/ash_approx_polish.txt
  org/apache/commons/codec/language/bm/ash_approx_romanian.txt
  org/apache/commons/codec/language/bm/ash_approx_russian.txt
  org/apache/commons/codec/language/bm/ash_approx_spanish.txt
  org/apache/commons/codec/language/bm/ash_exact_any.txt
  org/apache/commons/codec/language/bm/ash_exact_approx_common.txt
  org/apache/commons/codec/language/bm/ash_exact_common.txt
  org/apache/commons/codec/language/bm/ash_exact_cyrillic.txt
  org/apache/commons/codec/language/bm/ash_exact_english.txt
  org/apache/commons/codec/language/bm/ash_exact_french.txt
  org/apache/commons/codec/language/bm/ash_exact_german.txt
  org/apache/commons/codec/language/bm/ash_exact_hebrew.txt
  org/apache/commons/codec/language/bm/ash_exact_hungarian.txt
  org/apache/commons/codec/language/bm/ash_exact_polish.txt
  org/apache/commons/codec/language/bm/ash_exact_romanian.txt
  org/apache/commons/codec/language/bm/ash_exact_russian.txt
  org/apache/commons/codec/language/bm/ash_exact_spanish.txt
  org/apache/commons/codec/language/bm/ash_hebrew_common.txt
  org/apache/commons/codec/language/bm/ash_lang.txt
  org/apache/commons/codec/language/bm/ash_languages.txt
  org/apache/commons/codec/language/bm/ash_rules_any.txt
  org/apache/commons/codec/language/bm/ash_rules_cyrillic.txt
  org/apache/commons/codec/language/bm/ash_rules_english.txt
  org/apache/commons/codec/language/bm/ash_rules_french.txt
  org/apache/commons/codec/language/bm/ash_rules_german.txt
  org/apache/commons/codec/language/bm/ash_rules_hebrew.txt
  org/apache/commons/codec/language/bm/ash_rules_hungarian.txt
  org/apache/commons/codec/language/bm/ash_rules_polish.txt
  org/apache/commons/codec/language/bm/ash_rules_romanian.txt
  org/apache/commons/codec/language/bm/ash_rules_russian.txt
  org/apache/commons/codec/language/bm/ash_rules_spanish.txt
  org/apache/commons/codec/language/bm/gen_approx_any.txt
  org/apache/commons/codec/language/bm/gen_approx_arabic.txt
  org/apache/commons/codec/language/bm/gen_approx_common.txt
  org/apache/commons/codec/language/bm/gen_approx_cyrillic.txt
  org/apache/commons/codec/language/bm/gen_approx_czech.txt
  org/apache/commons/codec/language/bm/gen_approx_dutch.txt
  org/apache/commons/codec/language/bm/gen_approx_english.txt
  org/apache/commons/codec/language/bm/gen_approx_french.txt
  org/apache/commons/codec/language/bm/gen_approx_german.txt
  org/apache/commons/codec/language/bm/gen_approx_greek.txt
  org/apache/commons/codec/language/bm/gen_approx_greeklatin.txt
  org/apache/commons/codec/language/bm/gen_approx_hebrew.txt
  org/apache/commons/codec/language/bm/gen_approx_hungarian.txt
  org/apache/commons/codec/language/bm/gen_approx_italian.txt
  org/apache/commons/codec/language/bm/gen_approx_polish.txt
  org/apache/commons/codec/language/bm/gen_approx_portuguese.txt
  org/apache/commons/codec/language/bm/gen_approx_romanian.txt
  org/apache/commons/codec/language/bm/gen_approx_russian.txt
  org/apache/commons/codec/language/bm/gen_approx_spanish.txt
  org/apache/commons/codec/language/bm/gen_approx_turkish.txt
  org/apache/commons/codec/language/bm/gen_exact_any.txt
  org/apache/commons/codec/language/bm/gen_exact_approx_common.txt
  org/apache/commons/codec/language/bm/gen_exact_arabic.txt
  org/apache/commons/codec/language/bm/gen_exact_common.txt
  org/apache/commons/codec/language/bm/gen_exact_cyrillic.txt
  org/apache/commons/codec/language/bm/gen_exact_czech.txt
  org/apache/commons/codec/language/bm/gen_exact_dutch.txt
  org/apache/commons/codec/language/bm/gen_exact_english.txt
  org/apache/commons/codec/language/bm/gen_exact_french.txt
  org/apache/commons/codec/language/bm/gen_exact_german.txt
  org/apache/commons/codec/language/bm/gen_exact_greek.txt
  org/apache/commons/codec/language/bm/gen_exact_greeklatin.txt
  org/apache/commons/codec/language/bm/gen_exact_hebrew.txt
  org/apache/commons/codec/language/bm/gen_exact_hungarian.txt
  org/apache/commons/codec/language/bm/gen_exact_italian.txt
  org/apache/commons/codec/language/bm/gen_exact_polish.txt
  org/apache/commons/codec/language/bm/gen_exact_portuguese.txt
  org/apache/commons/codec/language/bm/gen_exact_romanian.txt
  org/apache/commons/codec/language/bm/gen_exact_russian.txt
  org/apache/commons/codec/language/bm/gen_exact_spanish.txt
  org/apache/commons/codec/language/bm/gen_exact_turkish.txt
  org/apache/commons/codec/language/bm/gen_hebrew_common.txt
  org/apache/commons/codec/language/bm/gen_lang.txt
  org/apache/commons/codec/language/bm/gen_languages.txt
  org/apache/commons/codec/language/bm/gen_rules_any.txt
  org/apache/commons/codec/language/bm/gen_rules_arabic.txt
  org/apache/commons/codec/language/bm/gen_rules_cyrillic.txt
  org/apache/commons/codec/language/bm/gen_rules_czech.txt
  org/apache/commons/codec/language/bm/gen_rules_dutch.txt
  org/apache/commons/codec/language/bm/gen_rules_english.txt
  org/apache/commons/codec/language/bm/gen_rules_french.txt
  org/apache/commons/codec/language/bm/gen_rules_german.txt
  org/apache/commons/codec/language/bm/gen_rules_greek.txt
  org/apache/commons/codec/language/bm/gen_rules_greeklatin.txt
  org/apache/commons/codec/language/bm/gen_rules_hebrew.txt
  org/apache/commons/codec/language/bm/gen_rules_hungarian.txt
  org/apache/commons/codec/language/bm/gen_rules_italian.txt
  org/apache/commons/codec/language/bm/gen_rules_polish.txt
  org/apache/commons/codec/language/bm/gen_rules_portuguese.txt
  org/apache/commons/codec/language/bm/gen_rules_romanian.txt
  org/apache/commons/codec/language/bm/gen_rules_russian.txt
  org/apache/commons/codec/language/bm/gen_rules_spanish.txt
  org/apache/commons/codec/language/bm/gen_rules_turkish.txt
  org/apache/commons/codec/language/bm/lang.txt
  org/apache/commons/codec/language/bm/sep_approx_any.txt
  org/apache/commons/codec/language/bm/sep_approx_common.txt
  org/apache/commons/codec/language/bm/sep_approx_french.txt
  org/apache/commons/codec/language/bm/sep_approx_hebrew.txt
  org/apache/commons/codec/language/bm/sep_approx_italian.txt
  org/apache/commons/codec/language/bm/sep_approx_portuguese.txt
  org/apache/commons/codec/language/bm/sep_approx_spanish.txt
  org/apache/commons/codec/language/bm/sep_exact_any.txt
  org/apache/commons/codec/language/bm/sep_exact_approx_common.txt
  org/apache/commons/codec/language/bm/sep_exact_common.txt
  org/apache/commons/codec/language/bm/sep_exact_french.txt
  org/apache/commons/codec/language/bm/sep_exact_hebrew.txt
  org/apache/commons/codec/language/bm/sep_exact_italian.txt
  org/apache/commons/codec/language/bm/sep_exact_portuguese.txt
  org/apache/commons/codec/language/bm/sep_exact_spanish.txt
  org/apache/commons/codec/language/bm/sep_hebrew_common.txt
  org/apache/commons/codec/language/bm/sep_lang.txt
  org/apache/commons/codec/language/bm/sep_languages.txt
  org/apache/commons/codec/language/bm/sep_rules_any.txt
  org/apache/commons/codec/language/bm/sep_rules_french.txt
  org/apache/commons/codec/language/bm/sep_rules_hebrew.txt
  org/apache/commons/codec/language/bm/sep_rules_italian.txt
  org/apache/commons/codec/language/bm/sep_rules_portuguese.txt
  org/apache/commons/codec/language/bm/sep_rules_spanish.txt
  org/apache/commons/codec/language/dmrules.txt
```

---

*Plano gerado pelo SK Code Editor — 31/05/2026, 17:23:43*