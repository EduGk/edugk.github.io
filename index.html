/* EZLINK — interacciones y configuración */
const EZLINK_CONFIG = {
  // Escribe el número comercial en formato internacional, solo dígitos.
  // Ejemplo de formato: 5917XXXXXXX. No incluyas +, espacios ni guiones.
    whatsappNumbers: {
        es: "59175522487",
        "pt-BR": "5511999999999"
    }  // Si el número queda vacío, los botones mostrarán un aviso en vez de abrir WhatsApp.
};

document.addEventListener("DOMContentLoaded", () => {
  const menuToggle = document.querySelector(".menu-toggle");
  const mainNav = document.querySelector(".main-nav");
  const navLinks = document.querySelectorAll(".nav-link");
  const toast = document.querySelector(".toast");
  let toastTimer;

  document.querySelector("#current-year").textContent = new Date().getFullYear();

  function showToast(message) {
    if (!toast) return;
    toast.textContent = message;
    toast.classList.add("show");
    window.clearTimeout(toastTimer);
    toastTimer = window.setTimeout(() => toast.classList.remove("show"), 3600);
  }

  function closeMenu() {
    if (!menuToggle || !mainNav) return;
    menuToggle.setAttribute("aria-expanded", "false");
    menuToggle.setAttribute("aria-label", "Abrir menú");
    mainNav.classList.remove("is-open");
    document.body.classList.remove("menu-open");
  }

  if (menuToggle && mainNav) {
    menuToggle.addEventListener("click", () => {
      const isOpen = menuToggle.getAttribute("aria-expanded") === "true";
      menuToggle.setAttribute("aria-expanded", String(!isOpen));
      menuToggle.setAttribute("aria-label", isOpen ? "Abrir menú" : "Cerrar menú");
      mainNav.classList.toggle("is-open", !isOpen);
      document.body.classList.toggle("menu-open", !isOpen);
    });

    navLinks.forEach(link => link.addEventListener("click", closeMenu));
    document.addEventListener("keydown", event => {
      if (event.key === "Escape") closeMenu();
    });
    document.addEventListener("click", event => {
      const isOpen = mainNav.classList.contains("is-open");
      if (isOpen && !mainNav.contains(event.target) && !menuToggle.contains(event.target)) closeMenu();
    });
  }

  function buildWhatsAppUrl(number, message) {
    const cleanNumber = number.replace(/\D/g, "");
    if (!cleanNumber) return "";
    return `https://wa.me/${cleanNumber}?text=${encodeURIComponent(message)}`;
  }

  document.querySelectorAll(".js-whatsapp").forEach(link => {
    const message = link.dataset.message || "Hola, quisiera recibir información sobre EZLINK.";
    const url = buildWhatsAppUrl(EZLINK_CONFIG.whatsappNumbers.es, message);

    if (url) {
      link.href = url;
    } else {
      link.href = "#contacto";
      link.removeAttribute("target");
      link.addEventListener("click", event => {
        event.preventDefault();
        showToast(document.documentElement.lang === "pt-BR"
          ? "O WhatsApp comercial ainda não está configurado. Em breve você poderá entrar em contato por este canal."
          : "El WhatsApp comercial todavía no está configurado. Pronto podrás contactarnos por este medio.");
      });
    }
  });

  // Animaciones discretas al entrar las secciones en pantalla.
  const revealItems = document.querySelectorAll(".reveal");
  if ("IntersectionObserver" in window) {
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add("is-visible");
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.12 });
    revealItems.forEach(item => observer.observe(item));
  } else {
    revealItems.forEach(item => item.classList.add("is-visible"));
  }


  // Selector de idioma: español (ES) y portugués brasileño (PT-BR).
  const languageButtons = document.querySelectorAll(".language-option");
  const translations = {
    "pt-BR": {
      brandSubtitle: "GESTÃO DE COBRANÇAS",
      copyright: "Todos os direitos reservados.",
      talentStamp: "CRESCEMOS<br>EM EQUIPE",
      nav: ["Início", "Serviços", "Sobre nós", "Trabalhe conosco", "Contato", "Solicitar informações"],
      footerNav: ["Serviços", "Sobre nós", "Trabalhe conosco", "Contato"],
      heroEyebrow: "SEU PARCEIRO NA GESTÃO DE COBRANÇAS",
      heroTitle: 'Mais do que cobranças,<br><em>geramos resultados.</em>',
      heroText: "Ajudamos empresas a gerenciar suas carteiras com processos profissionais de cobrança telefônica, acompanhamento organizado e atendimento centrado nas pessoas.",
        heroLink: 'Conheça nossos serviços <span aria-hidden="true">↓</span>',
      heroNote: "Gestão profissional. Comunicação humana. Acompanhamento constante.",
      trust: [
        ["Foco em resultados", "Processos orientados a objetivos"],
        ["Atendimento profissional", "Comunicação respeitosa"],
        ["Acompanhamento claro", "Gestão organizada da carteira"]
      ],
      servicesEyebrow: "NOSSOS SERVIÇOS",
      servicesTitle: "Soluções focadas<br>nas necessidades do seu negócio.",
      servicesIntro: "Cada carteira é diferente. Trabalhamos com processos estruturados para apoiar as empresas em seus objetivos de recuperação e atendimento ao cliente.",
      cards: [
        ["01 / CONTATO", "Cobrança telefônica", "Contato com clientes por meio de uma comunicação clara, profissional e voltada a facilitar acordos de pagamento."],
        ["02 / CONTROLE", "Acompanhamento de carteira", "Organização e acompanhamento das gestões para manter uma visão clara de cada etapa do processo."],
        ["03 / EXPERIÊNCIA", "Atendimento profissional", "Uma abordagem respeitosa em cada interação, cuidando da experiência do cliente e da comunicação da marca."],
        ["04 / MELHORIA", "Gestão orientada a objetivos", "Processos que dão continuidade à gestão e permitem trabalhar de forma consistente em direção às metas acordadas."]
      ],
      disclaimer: "Os serviços e escopos específicos são definidos conforme as necessidades e condições acordadas com cada cliente.",
      aboutEyebrow: "SOBRE A EZLINK",
      imageCaption: "Pessoas comprometidas. Processos bem definidos.",
      aboutTitle: "Profissionalismo em cada contato. Compromisso em cada gestão.",
      aboutP1: "Na EZLINK, somos focados na gestão de cobranças por meio de call center, combinando comunicação profissional com processos organizados de acompanhamento.",
      aboutP2: "Buscamos construir relações de trabalho baseadas na confiança, responsabilidade e compreensão clara dos objetivos de cada empresa.",
      values: [
        ["Comunicação humana", "Interações respeitosas e profissionais."],
        ["Gestão organizada", "Acompanhamento e continuidade em cada processo."],
        ["Trabalho em equipe", "Pessoas comprometidas com objetivos compartilhados."]
      ],
      aboutButton: 'Vamos conversar <span aria-hidden="true">↗</span>',
      talentEyebrow: "OPORTUNIDADES DE TRABALHO",
      talentTitle: "Seu talento pode se conectar a novas oportunidades.",
      talentText: "Tem interesse em se desenvolver em um ambiente de call center? Queremos conhecer pessoas responsáveis, com vontade de aprender e habilidades de comunicação.",
      talentPoints: [
        "Interesse em atendimento e comunicação com clientes",
        "Compromisso e responsabilidade",
        "Disposição para aprender e trabalhar em equipe"
      ],
      talentButton: 'Consultar oportunidades <span aria-hidden="true">↗</span>',
      talentNote: "As vagas e os requisitos dependem dos processos seletivos em andamento. Consultar não garante uma vaga.",
      contactEyebrow: "VAMOS CONVERSAR?",
      contactTitle: "Vamos nos conectar para<br>dar o próximo passo.",
      contactText: "Se você representa uma empresa interessada em nossos serviços ou deseja consultar oportunidades de trabalho, estamos à disposição para orientar você.",
      companyButton: 'Sou uma empresa <span aria-hidden="true">↗</span>',
      jobsButton: 'Busco oportunidades <span aria-hidden="true">↗</span>',
      footerTagline: "Gestão profissional. Comunicação humana.",
      footerBack: "Voltar ao topo ↑",
      toast: "O WhatsApp comercial ainda não está configurado. Em breve você poderá entrar em contato por este canal.",
      messages: {
        general: "Olá, gostaria de receber informações sobre a EZLINK.",
        services: "Olá, gostaria de receber informações sobre os serviços da EZLINK.",
        company: "Olá, represento uma empresa e gostaria de receber informações sobre os serviços da EZLINK.",
        jobs: "Olá, tenho interesse em oportunidades de trabalho na EZLINK. Poderiam informar se há vagas abertas e como me candidatar?",
        phone: "Olá, gostaria de receber informações sobre o serviço de cobrança telefônica da EZLINK.",
        portfolio: "Olá, gostaria de receber informações sobre acompanhamento e gestão de carteira com a EZLINK.",
        customer: "Olá, gostaria de conhecer a abordagem de atendimento ao cliente da EZLINK.",
        goals: "Olá, gostaria de conversar sobre os objetivos de gestão de cobranças da minha empresa.",
        partnership: "Olá, gostaria de conversar com a EZLINK sobre uma possível parceria empresarial."
      }
    },
    es: null
  };

  const spanishMessages = {
    general: "Hola, quisiera recibir información sobre EZLINK.",
    services: "Hola, quisiera recibir información sobre los servicios de EZLINK.",
    company: "Hola, represento a una empresa y quisiera recibir información sobre los servicios de EZLINK.",
    jobs: "Hola, estoy interesado/a en oportunidades laborales en EZLINK. ¿Podrían indicarme si hay convocatorias disponibles y cómo postular?",
    phone: "Hola, quisiera información sobre el servicio de cobranza telefónica de EZLINK.",
    portfolio: "Hola, quisiera información sobre seguimiento y gestión de cartera con EZLINK.",
    customer: "Hola, quisiera conocer el enfoque de atención al cliente de EZLINK.",
    goals: "Hola, quisiera conversar sobre los objetivos de gestión de cobranzas de mi empresa.",
    partnership: "Hola, quisiera conversar con EZLINK sobre una posible colaboración empresarial."
  };

  const originalMessages = new Map();
  document.querySelectorAll(".js-whatsapp").forEach(link => {
    originalMessages.set(link, link.dataset.message || spanishMessages.general);
  });

  function setText(selector, value) {
    const element = document.querySelector(selector);
    if (element) element.innerHTML = value;
  }

  function setTexts(selector, values) {
    document.querySelectorAll(selector).forEach((element, index) => {
      if (values[index] !== undefined) element.innerHTML = values[index];
    });
  }

  function applyLanguage(language) {
    const pt = language === "pt-BR";
    document.documentElement.lang = pt ? "pt-BR" : "es";
    languageButtons.forEach(button => {
      const selected = button.dataset.lang === language;
      button.classList.toggle("is-selected", selected);
      button.setAttribute("aria-pressed", String(selected));
    });

    const nav = pt
      ? translations["pt-BR"].nav
      : ["Inicio", "Servicios", "Nosotros", "Trabaja con nosotros", "Contacto", "Solicitar información"];
    setTexts(".nav-link", nav.slice(0, 5));
    const navCta = document.querySelector(".main-nav .js-whatsapp");
    if (navCta) navCta.lastChild.textContent = pt ? " Solicitar informações" : " Solicitar información";

    if (pt) {
      const t = translations["pt-BR"];
      setTexts(".footer-nav a", t.footerNav);
      setText(".talent-stamp small", t.talentStamp);
      setTexts(".brand-copy small", [t.brandSubtitle,t.brandSubtitle]);
      setText(".footer-bottom .container > span",`© ${new Date().getFullYear()} EZLINK. ${t.copyright}`);
      setText(".hero .eyebrow", `<span></span> ${t.heroEyebrow}`);
      setText(".hero h1", t.heroTitle);
      setText(".hero-text", t.heroText);
      setText(".hero-actions .text-link", t.heroLink);
      setText(".hero-note", `<span class="note-line"></span> ${t.heroNote}`);
      setTexts(".trust-grid > div", t.trust.map(item => `<span class="trust-icon">${item[0].slice(0,2) === "En" ? "01" : ""}</span>`)); // Replaced below to preserve the numbered badges.
      document.querySelectorAll(".trust-grid > div").forEach((el, i) => {
        const badge = el.querySelector(".trust-icon");
        const originalNumber = ["01", "02", "03"][i];
        el.innerHTML = `<span class="trust-icon">${originalNumber}</span><span><strong>${t.trust[i][0]}</strong><small>${t.trust[i][1]}</small></span>`;
      });
      setText(".services-section .eyebrow", t.servicesEyebrow);
      setText(".section-heading h2", t.servicesTitle);
      setText(".section-intro", t.servicesIntro);
      document.querySelectorAll(".service-card").forEach((card, i) => {
        const c = t.cards[i];
        card.querySelector(".card-number").textContent = c[0];
        card.querySelector("h3").textContent = c[1];
        card.querySelector("p").textContent = c[2];

      });
      setText(".disclaimer", t.disclaimer);
      setText(".about-copy .eyebrow", t.aboutEyebrow);
      setText(".image-caption", `<span class="caption-dot"></span> ${t.imageCaption}`);
      setText(".about-copy h2", t.aboutTitle);
      const aboutParagraphs = document.querySelectorAll(".about-copy > p:not(.eyebrow)");
      if (aboutParagraphs[0]) aboutParagraphs[0].textContent = t.aboutP1;
      if (aboutParagraphs[1]) aboutParagraphs[1].textContent = t.aboutP2;
      document.querySelectorAll(".values-list > div").forEach((el, i) => {
        el.innerHTML = `<span>✓</span><span><strong>${t.values[i][0]}</strong><small>${t.values[i][1]}</small></span>`;
      });
      setText(".about-copy .button", t.aboutButton);
      setText(".talent-copy .eyebrow", t.talentEyebrow);
      setText(".talent-copy h2", t.talentTitle);
      setText(".talent-copy > p:not(.eyebrow)", t.talentText);
      setTexts(".talent-points li", t.talentPoints.map(text => `<span>↗</span> ${text}`));
      setText(".talent-copy .button", t.talentButton);
      setText(".talent-note", t.talentNote);
      setText(".contact-content .eyebrow", t.contactEyebrow);
      setText(".contact-content h2", t.contactTitle);
      setText(".contact-content > p:not(.eyebrow)", t.contactText);
      setText(".contact-actions .button:first-child", t.companyButton);
      setText(".contact-actions .button:last-child", t.jobsButton);
      setText(".footer-main > p", t.footerTagline);
      setText(".footer-bottom a", t.footerBack);
      document.querySelector(".floating-whatsapp")?.setAttribute("aria-label", "Entrar em contato com a EZLINK pelo WhatsApp");
    } else {
      // Restaurar os textos originais em espanhol de forma consistente.
      location.reload();
      return;
    }

    document.querySelectorAll(".js-whatsapp").forEach(link => {
      const key = link.dataset.messageKey;
      let message = link.dataset.message || spanishMessages.general;
      if (pt) {
        const map = translations["pt-BR"].messages;
        if (link.closest(".talent-section") || link.dataset.message?.includes("oportunidades laborales")) message = map.jobs;
        else if (link.closest(".contact-actions") && link.classList.contains("js-whatsapp")) {
          message = link === document.querySelector(".contact-actions .button:first-child") ? map.company : map.jobs;
        } else if (link.dataset.message?.includes("cobranza telefónica")) message = map.phone;
        else if (link.dataset.message?.includes("seguimiento y gestión")) message = map.portfolio;
        else if (link.dataset.message?.includes("atención al cliente")) message = map.customer;
        else if (link.dataset.message?.includes("objetivos de gestión")) message = map.goals;
        else if (link.dataset.message?.includes("posible colaboración")) message = map.partnership;
        else if (link.dataset.message?.includes("servicios de gestión de cobranzas")) message = map.services;
        else if (link.dataset.message?.includes("servicios de EZLINK") || link === navCta) message = map.services;
        else message = map.general;
        link.dataset.message = message;
      }
      const url = buildWhatsAppUrl(EZLINK_CONFIG.whatsappNumbers[language], message);
      if (url) {
        link.href = url;
      } else {
        link.href = "#contacto";
      }
    });
  }

  // Guarda el idioma seleccionado durante la navegación actual.
  languageButtons.forEach(button => {
    button.addEventListener("click", () => {
      const language = button.dataset.lang;
      if (language === "es") {
        location.reload();
      } else {
        applyLanguage(language);
      }
    });
  });

  // Marca la sección visible en la navegación.
// Detectar la sección activa del menú
const sections = document.querySelectorAll("main section[id]");

function updateActiveNav() {
    const scrollPosition = window.scrollY + 150;

    let currentSection = "inicio";

    sections.forEach(section => {
        if (scrollPosition >= section.offsetTop) {
            currentSection = section.id;
        }
    });

    navLinks.forEach(link => {
        const isActive =
            link.getAttribute("href") === `#${currentSection}`;

        link.classList.toggle("active", isActive);
    });
}

// Actualizar al desplazarse
window.addEventListener("scroll", updateActiveNav, {
    passive: true
});

// Actualizar al cargar la página
updateActiveNav();
});
