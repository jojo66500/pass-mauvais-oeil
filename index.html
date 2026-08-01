import React, { useState, useEffect, useRef } from "react";

/* ============================================================
   PASS MAUVAIS ŒIL — Grimoire complet des traditions de protection
   Édition unique : tout le savoir accessible dès l'activation.
   Les emplacements d'images sont balisés IMG-01 à IMG-16.
   ============================================================ */

const FONTS = `
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400&family=EB+Garamond:ital,wght@0,400;0,500;1,400&family=Jost:wght@300;400;500&display=swap');
`;

const C = {
  nuit: "#10182B",
  nuitCarte: "#1B2540",
  nuitProfonde: "#0B111F",
  parchemin: "#F1E8D6",
  parcheminDoux: "#D8CDB6",
  or: "#C9A45C",
  orClair: "#E3C78A",
  nazar: "#4FA3B5",
  nazarClair: "#8FD3DE",
  ligne: "rgba(201,164,92,0.25)",
};

/* Codes de démonstration — en production : base serveur, codes uniques,
   liaison définitive au compte, blocage des duplications. */
const CODES_DEMO = ["PMO-2026-0001", "PMO-2026-0002", "PMO-2026-0003"];

/* ---------- Emblème Nazar ---------- */
function Nazar({ size = 72, glow = true }) {
  return (
    <div style={{ position: "relative", width: size, height: size, margin: "0 auto" }}>
      {glow && (
        <div style={{
          position: "absolute", inset: -size * 0.25, borderRadius: "50%",
          background: `radial-gradient(circle, ${C.nazar}33 0%, transparent 70%)`,
          animation: "respire 5s ease-in-out infinite",
        }} />
      )}
      <svg viewBox="0 0 100 100" width={size} height={size} style={{ position: "relative" }}>
        <circle cx="50" cy="50" r="46" fill="#1E3A5F" stroke={C.or} strokeWidth="1.5" />
        <circle cx="50" cy="50" r="33" fill="#F1E8D6" />
        <circle cx="50" cy="50" r="21" fill={C.nazar} />
        <circle cx="50" cy="50" r="10" fill="#10182B" />
        <circle cx="46" cy="46" r="3" fill="#F1E8D6" opacity="0.9" />
      </svg>
    </div>
  );
}

/* ---------- Emplacement d'image ----------
   Pour insérer une image : remplacer <ImageSlot id="IMG-XX" .../>
   par <img src="..." style={{width:'100%', borderRadius:14}} alt="..."/> */
function ImageSlot({ id, sujet, ratio = "16/9", src }) {
  // Si une image réelle est fournie (src), on l'affiche.
  // Sinon, on garde le cadre pointillé indiquant l'emplacement à remplir.
  if (src) {
    return (
      <img
        src={src}
        alt={sujet}
        style={{
          width: "100%", aspectRatio: ratio, objectFit: "cover",
          borderRadius: 14, margin: "4px 0 20px", display: "block",
        }}
      />
    );
  }
  return (
    <div style={{
      width: "100%", aspectRatio: ratio, borderRadius: 14, margin: "4px 0 20px",
      border: `1.5px dashed ${C.ligne}`, background: "rgba(255,255,255,0.02)",
      display: "flex", flexDirection: "column", alignItems: "center", justifyContent: "center",
      gap: 6, padding: 16, boxSizing: "border-box", textAlign: "center",
    }}>
      <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, letterSpacing: "0.2em", color: C.or }}>{id}</span>
      <span style={{ fontFamily: "'EB Garamond', serif", fontStyle: "italic", fontSize: 13, color: "#7A88A3", lineHeight: 1.5 }}>{sujet}</span>
    </div>
  );
}

/* ============================================================
   LE GRIMOIRE — chapitres complets
   ============================================================ */
const GRIMOIRE = [
  {
    id: "origines",
    titre: "Aux origines du mauvais œil",
    eyebrow: "Comprendre",
    resume: "Une croyance millénaire, de la Mésopotamie aux campagnes d'Europe.",
    img: { id: "IMG-02", sujet: "Œil nazar bleu turc ou fresque antique méditerranéenne représentant l'œil protecteur", src: "/images/img-02.jpg" },
    corps: [
      "La croyance au mauvais œil est l'une des plus anciennes de l'humanité. On la retrouve dès la Mésopotamie antique, en Grèce et à Rome, puis dans tout le bassin méditerranéen, au Maghreb, au Proche-Orient et dans les campagnes d'Europe — l'Italie du Sud avec la jettatura, la Corse avec l'occhju, la Provence, la Bretagne.",
      "À travers les yeux, enseigne la tradition, l'homme peut émettre une énergie — positive ou négative. Le mauvais œil serait cette énergie maléfique projetée par le regard, le plus souvent sans le savoir : il suffit qu'une pensée d'envie, de jalousie ou de rancœur accompagne le regard porté sur quelqu'un. C'est un acte involontaire que des millions de personnes accompliraient chaque jour.",
      "La tradition a même dressé le portrait-type du jeteur de sorts : grand, maigre, le nez long, les yeux petits et perçants, la peau olivâtre, grincheux, vêtu de sombre. Une caricature, bien sûr — mais elle dit combien nos ancêtres prenaient la chose au sérieux. On croyait aussi que le regard d'un mourant rempli de haine était centuplé en puissance : voilà pourquoi l'usage veut qu'on ferme immédiatement les yeux des morts.",
      "Les moments de colère, de peur ou de douleur rendraient la pensée plus puissante que ceux de joie : une personne en proie à une crise de rage émettrait, selon ces croyances, des pensées capables de causer un sérieux dommage à celui qu'elles visent.",
    ],
    note: "Le mauvais œil est involontaire ; le sortilège est un acte délibéré. Cette distinction fonde toute la tradition — et tout ce grimoire.",
  },
  {
    id: "signes",
    titre: "Reconnaître les signes",
    eyebrow: "Repérer",
    resume: "Fatigue, bâillements, série noire : ce que la tradition lit dans les indices.",
    img: { id: "IMG-03", sujet: "Bougie dont la flamme vacille dans la pénombre, ou miroir ancien piqué", src: "/images/img-03.jpg" },
    corps: [
      "Comment la tradition repérait-elle le mauvais œil ? D'abord par les états du corps et de l'esprit. Une fatigue inexpliquée et persistante, l'esprit encombré, un sommeil agité : autant de signes, disait-on, d'une aura vitale affaiblie. Les bâillements répétés en présence d'une personne étaient lus comme un véritable vol d'énergie — remarquez d'ailleurs que lorsqu'une personne bâille, sa voisine bâille à son tour : la tradition y voyait un transfert d'énergie entre les deux.",
      "Venaient ensuite les séries noires : les petits malheurs qui s'enchaînent sans logique — objets qui se cassent, projets qui échouent au dernier moment, disputes qui éclatent de nulle part, malchance qui colle. Un accident isolé n'inquiétait personne ; c'est l'accumulation qui éveillait le soupçon.",
      "La tradition disait aussi que le mauvais œil frappe volontiers là où fleurit le bonheur — le couple, la fécondité, la réussite — car c'est là que se concentre l'envie d'autrui. D'où la coutume de porter la mariée dans les bras pour franchir le seuil de la maison : on la protégeait du mauvais œil jeté par les jaloux sur le nouveau foyer.",
      "Pour les sortilèges, plus rares et plus graves, on guettait des signes dits « secondaires » : des marques étranges apparues sur les murs ou les carrelages, des taches rougeâtres inexpliquées sur les bras ou le dos, et surtout — c'était la première chose que l'on vérifiait — d'étranges formes découvertes dans les oreillers et matelas : nids, spirales, petits assemblages de plumes et de brins de laine entremêlés et noués.",
      "Enfin, les rêves. Le dormeur verrait en songe la personne qui lui envoie du mal ; parfois, ce sont des parents défunts qui viendraient l'avertir. La tradition y lisait le travail de l'inconscient, plus sensible que la veille, qui capte ce que le jour ne voit pas.",
    ],
    note: "Un signe isolé ne veut rien dire, répétaient les anciens eux-mêmes : c'est le faisceau d'indices qui parlait — et encore fallait-il le vérifier par les rites. Voir le chapitre suivant.",
  },
  {
    id: "rites-verification",
    titre: "Les rites de vérification",
    eyebrow: "Repérer",
    resume: "L'huile dans l'eau, l'encens, le sel, le plomb : les épreuves ancestrales.",
    img: { id: "IMG-04", sujet: "Gouttes d'huile d'olive à la surface d'une assiette d'eau, éclairées à la bougie", src: "/images/img-04.jpg" },
    corps: [
      "Avant de conclure au mauvais œil, la magie populaire soumettait le soupçon à l'épreuve. Ces rites, dont l'origine se perd dans la nuit des temps, reposent tous sur la magie de correspondance. Voici les principaux, tels que la tradition les a transmis.",
      "Le rite de l'huile — le plus célèbre, encore pratiqué dans toute la Méditerranée. Remplissez un petit bassin d'eau. Versez trois cuillerées d'huile d'olive dans une soucoupe. Allumez une bougie blanche avec une allumette en bois, éteignez toute autre lumière. Trempez l'index gauche dans l'huile et laissez tomber trois gouttes dans l'eau. Si les gouttes restent concentrées, tout va bien ; si elles se répandent en cercles concentriques, la tradition y lit une influence négative — d'autant plus forte que les cercles s'étendent. Une variante veut qu'on passe d'abord trois fois la soucoupe au-dessus de la tête de la personne concernée.",
      "Le rite de l'encens. Jetez une grosse pincée d'encens pur dans un bassin de cuivre et allumez-la avec une allumette en bois. Observez la fumée : blanche, il n'y a rien à craindre ; foncée, la tradition y voit des négativités — plus la fumée est sombre, plus elles seraient puissantes. Ce rite sert aussi à sonder une maison, et présente un avantage : en brûlant, l'encens purifie déjà les lieux.",
      "Le rite du sel. Placez 27 grains de gros sel dans un récipient de cuivre ou de terre cuite, versez dessus 7 cuillerées d'alcool et enflammez avec une allumette en bois. Si le sel crépite en brûlant, la tradition y entend des négativités — d'autant plus présentes que les crépitements sont bruyants.",
      "Le rite du plomb, pratiqué autrefois par les guérisseuses : on versait du plomb fondu dans un bassin d'eau, en présence de la personne. Les vapeurs, disait-on, éloignaient déjà les négativités ; les formes prises par le métal en se solidifiant en révélaient l'importance. On citera aussi le rite du buis (trois gouttes d'huile dans l'eau avec une feuille de buis bénit) et l'observation des yeux : l'opérateur qui ne voyait pas son propre reflet dans les yeux de la personne concluait au maléfice.",
      "Un détail traverse tous ces rites : l'allumette en bois. Jamais de briquet, jamais d'allumette soufrée moderne — le bois, matière vivante, était seul jugé digne de porter la flamme rituelle.",
    ],
    note: "Les anciens le savaient : ces rites éveillaient surtout l'intuition de celui qui les pratiquait. Neuf fois sur dix, concluaient les plus sages, il ne s'agissait que de pensées négatives ordinaires — que les protections de ce grimoire suffisent à dissiper.",
  },
  {
    id: "mauvais-oeil-sortilege",
    titre: "Mauvais œil, sortilèges et charlatans",
    eyebrow: "Comprendre",
    resume: "La grande distinction — et la mise en garde des maîtres anciens.",
    img: { id: "IMG-05", sujet: "Vieux grimoire ouvert, sceaux de cire, plume — atmosphère cabinet de curiosités", src: "/images/img-05.jpg" },
    corps: [
      "Le mauvais œil est une énergie négative envoyée le plus souvent involontairement. Le sortilège, lui, est un enchantement de magie noire : un acte toujours volontaire, accompli au moyen d'un rituel déterminé. C'est pourquoi la tradition le tient pour bien plus dangereux — et bien plus rare.",
      "Les maîtres anciens qui ont étudié ces questions livrent un chiffre frappant : dans 90 % des cas qu'ils examinaient, il ne s'agissait pas de sortilège, mais de pensées négatives plus ou moins fortes — envoyées, le plus souvent, par des membres de la famille même. La jalousie de proximité, disaient-ils, est la plus corrosive.",
      "La tradition décrit aussi le sort peu enviable du jeteur de sorts : celui qui met en marche ces énergies subit ou subira exactement les tourments qu'il cause à ses victimes. Il est la première victime de ses propres malédictions — c'est la loi du retour, sur laquelle nous reviendrons.",
      "Et puis il y a la mise en garde, transmise avec insistance : méfiez-vous de quiconque vous affirme que vous êtes ensorcelé. Les pseudo-voyants qui installent la peur du sortilège chez leur client pour vendre sa « levée » commettent, disent les textes, le pire des maléfices — car la pensée est créative : à force de croire au sortilège, le client finit réellement envoûté... par celui-là même qu'il était venu consulter. Le Pass Mauvais Œil est fidèle à cette sagesse : il vous donne les rites, les signes et les protections — le jugement vous appartient.",
    ],
    note: "Retenez la règle d'or des anciens : celui qui vous vend la peur vend aussi son antidote. La tradition authentique, elle, se transmet — elle ne se monnaye pas à coups de frayeur.",
  },
  {
    id: "sel",
    titre: "Le sel, gardien universel",
    eyebrow: "Se protéger",
    resume: "Trois grains dans la poche, une ligne au seuil : le plus ancien des boucliers.",
    img: { id: "IMG-06", sujet: "Gros sel en coupelle de terre cuite, lumière chaude, ambiance cuisine ancienne", src: "/images/img-06.jpg" },
    corps: [
      "De toutes les substances protectrices, le sel est la plus universelle. Incorruptible, il conserve ; blanc, il purifie ; précieux, il fut monnaie. Toutes les traditions lui prêtent le pouvoir d'éloigner les influences négatives.",
      "La coutume la plus connue concerne les fiancés : ceux qui craignent le mauvais œil doivent garder dans leur poche un petit paquet contenant trois grains de sel, jusqu'au jour du mariage. Trois grains — le chiffre de la perfection divine, actif et protecteur.",
      "Les guérisseurs de campagne pratiquaient le bas exorcisme avec le sel : ils en déposaient entre chaque doigt pour éloigner les esprits malins tenus pour responsables des maladies, ou brûlaient du sel pour chasser les influences. L'eau salée servait à se laver les mains avant de toucher tout objet suspect — précaution que la tradition recommande encore à qui découvre un « fruit » de sortilège (voir le chapitre sur la neutralisation).",
      "Dans la maison, une coupelle de gros sel posée dans une pièce absorberait, selon la croyance, les négativités ambiantes ; on renouvelle le sel régulièrement, en jetant l'ancien hors de la maison. Et lorsqu'on emménage dans un nouveau foyer, la coutume veut qu'on y entre avec du sel et du pain : la protection et l'abondance franchissent le seuil avec vous.",
    ],
    note: "Le rite des 27 grains, pour sonder une maison, est décrit au chapitre des rites de vérification.",
  },
  {
    id: "protections-populaires",
    titre: "Le répertoire des gestes protecteurs",
    eyebrow: "Se protéger",
    resume: "Fer à cheval, corail, turquoise, ail, fougère : l'arsenal des campagnes.",
    img: { id: "IMG-07", sujet: "Fer à cheval ancien cloué sur porte en bois, tresse d'ail, branche de corail rouge", src: "/images/img-07.jpg" },
    corps: [
      "Les traditions populaires ont transmis un répertoire foisonnant, fondé sur la magie d'affinité et d'analogie. En voici l'essentiel, tel que les anciens le pratiquaient.",
      "Pour la maison : le fer à cheval cloué sur la porte préserve du mauvais œil — mais pour être pleinement efficace, il doit être trouvé, jamais acheté ni reçu. L'ail pendu à la porte ou gardé en poche protège ; on purifie même l'intérieur des casseroles neuves en le frottant d'ail, et les ciseaux après une coupe de cheveux. Une brosse placée derrière la porte empêche les esprits malins d'entrer — attention : laissée devant la porte, elle offense les visiteurs. Les graines de fougère éloignent le mauvais œil, les esprits malins et les fantômes. On parsème le lit de persil. Et l'on garde chez soi un chat noir — nous lui consacrons un chapitre entier.",
      "Sur soi : les vêtements turquoise protègent du mauvais œil et des esprits malins — c'est la couleur du nazar, l'œil bleu des traditions turques et grecques, et la turquoise elle-même, que les Arabes nommaient « pierre de la santé », se portait en talisman sur le front. Les bijoux de corail rouge protègent depuis l'Antiquité romaine — on en attachait aux berceaux des nouveau-nés. Un sachet de soie verte contenant un aimant se porte contre soi. Une épine de rose gardée dans le portefeuille éloigne le mal.",
      "Les gestes d'urgence : lorsqu'on croise une personne négative, la tradition ordonne de cracher par terre et d'effacer le crachat du pied gauche. Pour couper un flux d'énergie qu'on sent peser sur soi : croiser les jambes ou les mains, ou refermer les pouces à l'intérieur des paumes et serrer les autres doigts dessus, en poings fermés. Et l'on se couvre la bouche en bâillant — sans quoi, dit la croyance, un esprit malin pourrait s'engouffrer.",
      "Ces techniques simples suffisent contre les énergies faibles du quotidien. Contre des influences plus fortes, la tradition prescrit les amulettes, les talismans, les pentacles — et le bouclier de la pensée. Les chapitres qui suivent vous donnent tout.",
    ],
    note: "Le mardi ou le samedi, en lune décroissante, brossez la maison en pensant en déloger toute influence : c'est le grand ménage symbolique, détaillé dans les Rituels.",
  },
  {
    id: "amulettes",
    titre: "Les amulettes",
    eyebrow: "Objets de pouvoir",
    resume: "Cornes, miroirs, œil, trèfle : les porte-bonheur nés de la nature.",
    img: { id: "IMG-08", sujet: "Collection d'amulettes : corne italienne rouge (corno), main de Fatma, petit miroir, trèfle sous verre", src: "/images/img-08.jpg" },
    corps: [
      "L'amulette est le porte-bonheur le plus ancien de l'humanité : simple, passif, protecteur, capable d'annuler les petites vibrations malveillantes du quotidien. Plaques de métal à l'effigie d'une divinité ou d'un saint, parties d'animaux — cornes, dents, griffes —, fragments végétaux cousus dans de petits sachets portés à même la peau : autrefois, on en cachait jusque dans les cannes.",
      "La corne — celle que tant d'automobilistes accrochent encore au rétroviseur — est le symbole de Diane, déesse de la chasse, et sa forme rappelle le croissant de lune. Elle protège les enfants et les femmes enceintes. Le miroir, ou n'importe quel objet brillant porté sur soi, fait fuir le démon : s'y regardant, il s'enfuit terrifié par sa propre image. L'œil rappelle le symbole du Soleil — c'est l'amulette même de ce grimoire. Le trèfle à quatre feuilles représente la Croix ; sept épis de blé, la prospérité et la fécondité.",
      "Les amulettes animales transmettent les vertus de l'animal : le lion (une dent, quelques poils) donne le courage ; le renard, l'habileté et la chance en affaires ; la tortue assure longue vie et protège de la sorcellerie ; le scarabée donne la santé et protège de tous les dangers ; la grenouille est propice à l'amour et à l'amitié ; la tête de serpent protège de toutes les maladies ; la griffe d'aigle rend puissant ; la grue promet une vie longue et saine.",
      "L'analogie est la clé : en portant une partie ou l'image d'un être, on s'approprie sa force dominante. Jetez un œil dans les voitures autour de vous — chapelets, cornes, images saintes suspendues : l'homme moderne n'a jamais cessé de porter des amulettes.",
    ],
    note: "L'amulette agit par sa seule matière. Le talisman, lui, se fabrique et se charge : c'est l'étape supérieure.",
  },
  {
    id: "talismans",
    titre: "Les talismans",
    eyebrow: "Objets de pouvoir",
    resume: "Personnels, gravés, chargés : les protecteurs sur mesure — et les pierres de votre signe.",
    img: { id: "IMG-09", sujet: "Pierres précieuses et semi-précieuses sur velours sombre : turquoise, améthyste, corail, émeraude", src: "/images/img-09.jpg" },
    corps: [
      "Le talisman est une protection d'un degré supérieur : personnel, il est lié au nom de son propriétaire ou aux caractéristiques de son signe zodiacal. Autrefois, on y gravait le nom secret de la personne sous forme de symbole — car connaître le nom secret d'un homme, c'est le posséder ; en Égypte, seul le pharaon osait écrire son nom en entier.",
      "Le talisman se porte : boucle d'oreille, bracelet, chaînette. Il fonctionne parce qu'il concentre une énergie que les vieilles croyances nomment manas, présente dans tout l'univers, et parce qu'il renferme les informations du macrocosme — planète, constellation, animal, métal correspondants. Le plus commun est le fer à cheval trouvé : forme de lune, fer qui éloigne les démons, cheval symbole d'intelligence — l'un des plus puissants qui soient.",
      "Le talisman se charge. L'imprégnation se fait d'elle-même par le port prolongé : plus il reste au contact de son propriétaire, plus il est efficace. On peut aussi le magnétiser : le tenir en main en pensant intensément que l'énergie de la main le charge. L'encens et la myrrhe deviennent eux-mêmes de puissants talismans — il suffit d'en porter toujours trois grains sur soi.",
      "Chaque signe a ses pierres : Bélier — rubis et améthyste ; Taureau — saphir et zircon ; Gémeaux — agate et aigue-marine ; Cancer — perle et émeraude ; Lion — brillant et topaze ; Vierge — jade et cornaline ; Balance — diamant et lapis ; Scorpion — rubis et topaze ; Sagittaire — turquoise et grenat ; Capricorne — onyx et chrysolithe ; Verseau — grenat et saphir ; Poissons — corail et aigue-marine.",
      "Et chaque pierre, ses vertus : la turquoise protège du mauvais œil et des esprits malins ; l'émeraude aussi, en renforçant la vue et la mémoire ; l'améthyste porte chance en amour et affermit le jugement ; le corail donne la prudence et fait grandir les enfants en bonne santé ; le saphir porté au front calme et porte chance ; le grenat protège en voyage ; le rubis conserve la jeunesse et guérit les mélancolies. Les pierres ont accumulé leurs énergies pendant des millions d'années — elles sont, disent les textes, un souffle de l'éternité.",
    ],
    note: "Une légende chinoise enseigne que chaque âme est reliée par un rayon d'or à une étoile du ciel. Dessiner son étoile et ses voisines : voilà le « talisman de l'étoile personnelle ».",
  },
  {
    id: "pentacles",
    titre: "Les pentacles",
    eyebrow: "Objets de pouvoir",
    resume: "Pentagramme et sceau de Salomon : les figures maîtresses de la protection.",
    img: { id: "IMG-10", sujet: "Pentagramme et hexagramme tracés à l'encre dorée sur parchemin, style grimoire Renaissance", src: "/images/img-10.jpg" },
    corps: [
      "Au sommet de la hiérarchie des objets protecteurs règne le pentacle : figure géométrique tracée selon des règles précises, capable de renfermer des centaines d'informations — autant qu'un livre entier. Dans les vrais livres de magie, un pentacle en couverture ou en première page résume la signification de tout l'ouvrage. Jusqu'à l'encre qui le trace est préparée selon des règles précises.",
      "Le pentagramme, ou étoile flamboyante à cinq branches, est le pentacle de la protection et du bonheur. Le cinq est le chiffre de l'homme, le microcosme : cinq sens, cinq planètes anciennes, cinq plaies du Christ auxquelles on l'identifie. Sa couleur est le rouge vermeil, couleur du sang et de la force. Les esprits malins s'éloignent et les élémentaires se soumettent à sa seule vue. Il représente non pas l'homme individuel, mais l'homme total — l'union de tous les hommes en un seul.",
      "L'hexagramme, ou sceau de Salomon, est l'étoile à six branches formée de deux triangles entrelacés : le feu qui monte, l'eau qui descend — l'union des contraires, l'équilibre parfait des forces. Avec le pentagramme, il regroupe les énergies magiques les plus importantes de la tradition occidentale.",
      "Le grand Paracelse soignait, dit-on, des troubles graves en plaçant au cou du malade le pentacle adéquat, créé au bon moment astrologique et dans les métaux convenant au but. La tradition prête même au pentacle une forme d'intelligence : il laisserait parfois survenir des épreuves... parce qu'elles font partie du chemin de celui qui le porte, et le renforcent. Combien de chefs-d'œuvre sont nés des coups durs du destin ?",
      "Armoiries, blasons, sceaux de cire des documents anciens : tous étaient tenus pour talismans et pentacles. Les cloches elles-mêmes étaient magiques par leurs vibrations spirituelles. L'homme n'a jamais cessé de chercher, dans un symbole, une aide supérieure.",
    ],
    note: "Celui qui manipule un objet suspect endosse un pentacle de protection et circonscrit mentalement l'objet dans un cercle — voir le chapitre sur la neutralisation.",
  },
  {
    id: "cocon",
    titre: "Le bouclier de la pensée",
    eyebrow: "Se protéger",
    resume: "Le Cocon doré, l'aura vitale et la plus haute des protections.",
    img: { id: "IMG-11", sujet: "Silhouette en méditation enveloppée d'un halo doré, style illustration symboliste", src: "/images/img-11.jpg" },
    corps: [
      "Un projectile réel s'arrête avec un mur ; un projectile pensé, avec une barrière psychique. Toute la logique des protections mentales tient dans cette phrase des maîtres anciens. Contre les pensées négatives, il faut des défenses du même ordre.",
      "Chacun de nous vit dans son aura vitale — l'ensemble des énergies de nos corps subtils, comme un grand œuf d'émanations. Forte, elle rend invulnérable ; affaiblie par la fatigue, la peur ou le doute, elle laisse entrer les pensées négatives. Tout l'art consiste à la renforcer.",
      "L'exercice majeur est le Cocon doré : envelopper son corps, par la visualisation, d'une enveloppe de lumière dorée impénétrable, en s'appuyant sur des phrases spéciales conçues pour l'autosuggestion. Pratiqué régulièrement, il constitue la protection la plus fiable de tout le répertoire. Une version rapide existe pour les situations d'urgence : moins profonde, elle protège néanmoins une heure ou davantage. Les deux sont guidées pas à pas dans l'onglet Rituels.",
      "Mais la plus grande énergie, la plus parfaite, la plus pure, est l'amour. Plus nous sommes aimés, plus nous sommes protégés ; et quand nous donnons de l'amour, il se crée autour de nous une barrière insurmontable. L'homme bon et sage, disent les textes, vit sur un plan supérieur : lui jeter le mauvais œil serait comme lancer des flèches à ras du sol contre quelqu'un perché en haut d'un arbre.",
      "D'où la plus belle des contre-mesures traditionnelles : pendant neuf jours de suite, envoyer une fleur à la personne qui vous a fait du mal. Le geste ne fonctionne que s'il est sincère — mais alors, disent les anciens, il désarme tout.",
    ],
    note: "Variante rusée de la tradition : si vous savez qu'on trame contre vous, soyez d'une gentillesse extrême avec cette personne, et laissez-lui comprendre que vous savez. Le trouble qui s'ensuit suffit généralement à tout arrêter.",
  },
  {
    id: "purification",
    titre: "La purification de la maison",
    eyebrow: "Le foyer",
    resume: "Encens, bougies marquées de croix, brosse et lune décroissante.",
    img: { id: "IMG-12", sujet: "Fumée d'encens s'élevant devant une porte ancienne entrouverte, rai de lumière", src: "/images/img-12.jpg" },
    corps: [
      "Chaque maison s'imprègne des pensées de ses habitants. Là où règnent la paix et l'entente, on respire un air qui enrichit et détend ; là où l'on se querelle sans cesse, l'air est saturé de tension — et les personnes sensibles le ressentent dès le seuil. Chaque ville, chaque quartier porte de même l'empreinte de ceux qui l'habitent.",
      "Purifier la maison, c'est en déloger ces imprégnations. La bénédiction des maisons avant Noël et Pâques, encore pratiquée par l'Église, est la forme la plus haute de ce rituel — pourvu que le prêtre l'accomplisse avec foi. À côté d'elle, la tradition populaire a transmis ses propres méthodes, parfois exécutées par le plus âgé de la famille.",
      "L'encens d'abord : brûlez-le devant l'entrée principale et à proximité de chaque ouverture, fenêtres comprises. En grains, on en brûle 7 ou 9 ; en poudre, 3 pincées ; en bâtonnets, toujours un nombre impair — car l'impair marque l'accomplissement et la perfection, quand le pair signale l'attente. Toujours avec une allumette en bois. L'encens brûlé se conserve ensuite dans un flacon de verre fumé, placé sur le balcon.",
      "Les bougies ensuite : allumez trois bougies sur chacune desquelles vous aurez tracé trois croix ; chaque jour, ajoutez-en une, jusqu'à neuf bougies allumées.",
      "La brosse enfin : un mardi ou un samedi, en lune décroissante — quand la lune diminue, ce qu'on chasse diminue avec elle —, brossez toute la maison en pensant intensément en chasser toute force négative, puis placez la brosse derrière la porte pour barrer la route aux influences. La myrrhe complète l'encens dans les fumigations : elle éloigne les tentations et protège des sortilèges d'amour.",
    ],
    note: "Ces trois rituels sont guidés pas à pas dans l'onglet Rituels.",
  },
  {
    id: "plantes",
    titre: "Le bien et le mal dans les plantes",
    eyebrow: "Nature",
    resume: "Encens, myrrhe, noisetier — et la nuit magique de la Saint-Jean.",
    img: { id: "IMG-13", sujet: "Feu de la Saint-Jean au crépuscule, ou herbes séchées suspendues : millepertuis, lavande, fougère", src: "/images/img-13.jpg" },
    corps: [
      "La magie verte attribue aux plantes des vertus précises, et la science moderne lui donne parfois raison : les anciens n'adoraient pas l'ail ou l'oignon, ils en utilisaient l'énergie. Chaque odeur végétale est une énergie véritable, qui provoque des réactions, des sentiments — les animaux le savent d'instinct.",
      "L'encens règne sur toutes les religions, des hindous aux catholiques. Gomme-résine tirée d'arbres d'Arabie et d'Afrique, il dilate l'esprit, facilite l'extase mystique, et sa fumée éloigne tout ce qui est négatif : elle est la spiritualité même, le véhicule de l'amour, le souffle qui monte vers le divin. La myrrhe, sa sœur, agit sur le corps : elle éloigne les tentations les plus basses et protège des sortilèges d'amour et des infections. Avec l'or, elles furent les présents des Rois Mages — des initiés, des « connaisseurs des forces de la nature », dont les cadeaux étaient trois forces et non trois objets.",
      "La magie des plantes atteint son apogée une nuit par an : la nuit de la Saint-Jean, le 24 juin, écho du solstice d'été. Ce jour-là, le Soleil au plus haut entre dans le Cancer, et toutes les plantes possèdent des pouvoirs qu'elles n'auront plus les autres jours. Entre vingt-trois heures et minuit, les sourciers taillent leur baguette divinatoire dans le noisetier.",
      "Cueillies cette nuit-là, les herbes de la Saint-Jean — millepertuis en tête — se suspendent séchées dans la maison pour la protéger l'année entière. C'est la fête de l'amour et du feu, encore célébrée dans nombre de régions de France : un patrimoine vivant, entre botanique, calendrier solaire et poésie populaire.",
    ],
    note: "Trois grains d'encens et de myrrhe portés sur soi : le plus simple des talismans végétaux.",
  },
  {
    id: "animaux",
    titre: "Le bien et le mal dans les animaux",
    eyebrow: "Nature",
    resume: "Le chat, absorbeur de négativité — et la réhabilitation du crapaud.",
    img: { id: "IMG-14", sujet: "Chat noir aux yeux dorés sur un rebord de fenêtre au crépuscule, élégant, non inquiétant", src: "/images/img-14.jpg" },
    corps: [
      "Le chat est l'animal le plus extraordinaire du répertoire : il est le seul, dit la tradition, à se nourrir de négativité. Il absorbe tout ce qu'il y a de négatif dans le lieu où il vit — du simple énervement jusqu'aux formes-pensées les plus lourdes. Quelqu'un est fatigué, anxieux, nerveux ? Le chat vient spontanément se coucher près de lui, pour absorber cette énergie qui est sa nourriture.",
      "Garder un chat chez soi, c'est donc disposer d'un compagnon, d'un guérisseur et d'un gardien : il préserve la maison du mauvais œil, des sortilèges, des incendies, de la foudre. Le chat à trois couleurs protège des incendies ; le noir protège maison et jardin ; celui qui possède des griffes doubles est le meilleur porte-bonheur qui soit. Les connaisseurs de l'occulte s'entourent traditionnellement de trois chats, de préférence noirs — les meilleurs absorbeurs —, pour se prémunir des attaques psychiques et des chocs en retour.",
      "Les sept planètes vivent en lui : la méfiance de Saturne, la vitalité de Jupiter, la sensualité de Vénus, l'agressivité de Mars, l'astuce de Mercure, l'indépendance du Soleil ; ses pupilles qui se dilatent et se rétractent figurent la Lune et ses phases. On lui prête la vue éthérée : il voit ce que nous ne voyons pas — d'où l'antique conseil de ne pas le laisser dans la chambre d'un défunt.",
      "Quant au crapaud, si torturé par la sorcellerie d'autrefois qui en avait fait son animal favori, la tradition éclairée le réhabilite pleinement : cet animal nocturne à l'aspect ingrat est en réalité l'allié de l'homme et du jardinier. Les apparences, en magie comme ailleurs, sont les premières trompeuses.",
    ],
    note: "Peur du chat noir qui traverse la route ? La tradition la plus ancienne dit exactement l'inverse : il porte chance et attire la protection.",
  },
  {
    id: "retour",
    titre: "Le coup en retour",
    eyebrow: "Les lois occultes",
    resume: "Qui sème le mal le récolte : la loi du choc en retour.",
    img: { id: "IMG-15", sujet: "Boomerang ancien ou vague se brisant sur elle-même — métaphore visuelle du retour", src: "/images/img-15.jpg" },
    corps: [
      "C'est la grande loi morale de toute la tradition : l'énergie négative envoyée finit par revenir à son expéditeur. Le jeteur de sorts subit ou subira exactement les tourments qu'il cause — il est la première victime de ses malédictions.",
      "La tradition décrit le mécanisme : lorsqu'une énergie négative ne trouve pas prise sur sa cible — parce qu'elle est protégée, ou simplement trop sereine pour l'accueillir —, cette énergie ne se dissout pas : elle retourne à celui qui l'a émise, chargée de tout son poids. Voilà pourquoi les personnes protégées n'ont, au fond, rien à faire : leur bouclier travaille pour elles.",
      "Les praticiens de l'ombre le savent si bien qu'ils s'entourent de protections contre leurs propres retours : chats noirs absorbeurs, poupées baptisées de noms propres disposées dans la pièce pour égarer l'énergie qui revient — comme chercher une personne cachée parmi des centaines de mannequins.",
      "Quant au sorcier lui-même, la tradition lui promet un destin sombre : les basses entités qui lui prêtent leurs pouvoirs se servent de lui tant qu'il leur est utile — puis s'en débarrassent. La leçon est limpide, et elle vaut pour chacun de nous à l'échelle de nos petites jalousies quotidiennes : toute pensée de haine, d'envie, d'égoïsme alimente notre propre réservoir noir. Le mal que l'on pense est déjà un mal que l'on se fait.",
    ],
    note: "La meilleure « vengeance » de la tradition : les neuf fleurs de la réconciliation. Élégant, imparable — et le retour travaille tout seul.",
  },
  {
    id: "neutralisation",
    titre: "Neutraliser : les contre-mesures",
    eyebrow: "Les lois occultes",
    resume: "Que faire si l'on découvre un objet suspect — et pourquoi il ne faut jamais le brûler.",
    img: { id: "IMG-16", sujet: "Tissu noir plié, cire blanche, bol d'eau salée sur table de bois brut", src: "/images/img-16.jpg" },
    corps: [
      "La tradition nomme « fruits » les objets utilisés pour vitaliser un sortilège — assemblages étranges trouvés dans un oreiller, un matelas, un recoin de la maison. Si pareille découverte vous arrive, voici exactement ce que prescrit la tradition.",
      "Premier réflexe : la prudence. L'idéal est de ne pas toucher l'objet soi-même. Si l'on doit intervenir, la tradition impose de se laver d'abord les mains à l'eau salée et de se faire couler de la cire blanche sur les doigts, pour être protégé. L'objet est ensuite enfermé dans un morceau de tissu noir — jamais synthétique — ou de papier noir.",
      "Deuxième règle, capitale : ne jamais brûler l'objet. C'est l'erreur la plus courante. Le feu purifie, certes — mais il transforme : les énergies, dit la tradition, ne seraient que déplacées et continueraient d'agir sur un autre plan. Et l'on perdrait toute possibilité de comprendre ce dont il s'agissait.",
      "La neutralisation véritable interrompt le contact entre l'objet et son expéditeur, et vide complètement la matière de ses imprégnations. La tradition raconte qu'au moment principal du rite, lorsque l'objet est traité, le commanditaire du sortilège vient frapper à la porte de la maison — et que personne ne doit ouvrir. Il existe aussi une neutralisation préventive, appliquée notamment aux photos que l'on offre : elle efface de l'image toute charge psychique, la rendant inutilisable par d'éventuels malveillants.",
      "Enfin, contre les pensées négatives ordinaires — le cas de loin le plus fréquent —, nul besoin de tout cela : le Cocon doré, la purification de la maison et les protections du répertoire suffisent amplement. La tradition est unanime : neuf cas sur dix se dissolvent dans la sérénité retrouvée.",
    ],
    note: "Curiosité de la tradition : les chaînes de lettres « magiques » d'autrefois perdaient leur force à mesure qu'on les photocopiait — l'énergie envoyée se diluait. La technologie moderne, concluent les textes avec malice, a presque vidé ce vieux procédé de tout pouvoir.",
  },
  {
    id: "vampirisme",
    titre: "Vampirisme et attaques psychiques",
    eyebrow: "Les lois occultes",
    resume: "Ces présences qui épuisent : reconnaître les voleurs d'énergie.",
    img: { id: "IMG-17", sujet: "Deux silhouettes face à face, l'une lumineuse l'autre estompée — transfert d'énergie suggéré", src: "/images/img-17.jpg" },
    corps: [
      "Vous connaissez cette expérience : après une heure passée avec certaines personnes, vous êtes vidé — sans raison, sans dispute, sans effort. La tradition nomme cela le vampirisme psychique : certains êtres, souvent sans le savoir, se nourrissent de l'énergie vitale de leur entourage.",
      "Le bâillement en chaîne en est le signe le plus quotidien : lorsqu'une personne bâille et que vous bâillez à sa suite, un véritable transfert d'énergie s'opère entre vous. Le bâillement lui-même signale une carence d'énergie : les barrières immunitaires psychiques s'affaiblissent, l'aura vitale diminue, et les pensées négatives entrent plus facilement.",
      "Les parades de la tradition sont simples et discrètes : croiser les jambes ou les mains pour interrompre le flux magnétique ; refermer les pouces dans les paumes, doigts serrés dessus, en poings fermés ; se couvrir la bouche en bâillant. Ces gestes suffisent contre les énergies faibles. Pour les présences réellement épuisantes, le Cocon doré s'impose avant la rencontre — et sa version rapide, en urgence, protège une heure durant.",
      "Rappelons enfin la hiérarchie des remèdes : l'énergie la plus haute reste l'amour et la pensée positive. Le sage vit sur un plan que les voleurs d'énergie n'atteignent pas. Renforcez votre aura par la sérénité, la bienveillance et les pratiques de ce grimoire : vous cesserez d'être une proie sans jamais avoir eu à combattre.",
    ],
    note: "Après une rencontre éprouvante : quelques minutes de Cocon doré, une douche, et si possible la compagnie d'un chat — le grand absorbeur de négativité.",
  },
  {
    id: "corps-etherique",
    titre: "Le corps éthérique et l'anatomie subtile",
    eyebrow: "Autodéfense psychique",
    resume: "Chakras, nadis, méridiens : la carte secrète de vos défenses invisibles.",
    img: { id: "IMG-18", sujet: "Silhouette humaine avec les sept chakras illustrés en couleurs, style planche ésotérique élégante", src: "/images/img-18.jpg" },
    corps: [
      "Autour et au travers du corps physique, les traditions décrivent un champ d'énergie électromagnétique : le corps éthérique, réplique énergétique du corps qui guide ses fonctions — le « corps vital », disent les textes, ou plus poétiquement le « corps électrique ». Cette anatomie subtile est reconnue depuis toujours par les traditions orientales.",
      "Elle s'organise en trois réseaux : les chakras, sept centres d'énergie flamboyants qui filtrent, transforment et conduisent des qualités énergétiques correspondant aux énergies planétaires ; les nadis, canaux qui connectent les chakras et transmettent leurs énergies ; et les méridiens, réseau qui fait circuler l'énergie dans le corps entier — celui-là même qu'utilise l'acupuncture chinoise.",
      "Au-dessus du corps éthérique, la tradition place le corps émotionnel — le « cœur », siège des émotions, attirances et répulsions. C'est lui le maillon fragile : facilement endommagé par les expériences négatives et par nos propres états — l'envie, la haine, l'apitoiement sur soi-même. Les maladies, disent les textes, se manifestent souvent d'abord dans le corps émotionnel, et ses fuites peuvent attirer des prédateurs du plan astral.",
      "Son remède est aussi simple à énoncer que profond à pratiquer : le corps émotionnel s'équilibre par l'amour inconditionnel. On retrouve ici, formulée dans le langage de l'anatomie subtile, la grande loi de tout ce grimoire : la sérénité et la bienveillance sont la première des armures.",
    ],
    note: "Des exercices physiques traditionnels renforcent ce corps subtil — postures accroupies, appuis en forme de cœur sous le plexus solaire — que la tradition associe aux pratiques de méditation qui suivent.",
  },
  {
    id: "bouclier-foyer",
    titre: "L'eau salée et les objets gardiens",
    eyebrow: "Autodéfense psychique",
    resume: "Laver les murs à l'eau salée, exposer des bols, dresser le cercle : le bouclier domestique.",
    img: { id: "IMG-19", sujet: "Bol d'eau claire et gros sel près d'une fenêtre, lumière du matin, icône ou statuette en arrière-plan", src: "/images/img-19.jpg" },
    corps: [
      "Comme le sel, l'eau absorbe les négativités — et leur alliance fait le grand purificateur domestique de la tradition. Les murs et le sol d'une pièce peuvent être lavés à l'eau salée : une couche fraîche assainit l'atmosphère entière du lieu.",
      "Exposée dans des bols, l'eau travaille silencieusement : elle capte les influences ambiantes — on la renouvelle régulièrement, en la jetant hors de la maison. Placée sous le lit, elle protège des perturbations nocturnes. Et le sel versé en cercle autour d'un lieu ou d'une personne forme la plus ancienne des enceintes protectrices.",
      "La maison se défend aussi par ses objets. Icônes religieuses, croix, crucifix, bouddhas, statues et amulettes chargées sont à la fois protecteurs et beaux : connectés aux forces divines qu'ils symbolisent, ils peuvent émaner l'énergie divine — particulièrement si on les révère et les entretient. Les cristaux et les gemmes protègent de même, à condition d'être nettoyés très souvent à l'eau courante — l'idéal étant l'eau vive d'un ruisseau.",
      "Enfin, la tradition rappelle que les esprits n'aiment pas le fer : un objet de fer au seuil — le fer à cheval en est l'illustre exemple — barre la route aux influences. Entre le sel, l'eau, le fer et les images saintes, le foyer traditionnel était une véritable forteresse... qui ne coûtait presque rien.",
    ],
    note: "Le rituel complet du bouclier d'eau salée est guidé pas à pas dans l'onglet Rituels.",
  },
  {
    id: "meditation",
    titre: "La méditation du Pharaon",
    eyebrow: "Pratiques de l'esprit",
    resume: "La posture du Dieu égyptien : l'assise royale qui équilibre et protège.",
    img: { id: "IMG-20", sujet: "Statue égyptienne assise (pharaon, mains sur les cuisses) ou personne méditant dans cette posture", src: "/images/img-20.jpg" },
    corps: [
      "La plupart des techniques de méditation de la magie occidentale sont tirées de traditions anciennes, et la posture de départ la plus classique est celle dite du « Pharaon » ou du « Dieu égyptien » — celle-là même des statues assises de l'Égypte : dos droit, majesté immobile. Elle promeut le bien-être et l'équilibre intérieur.",
      "Son cœur est un cycle respiratoire carré : inspirer en comptant jusqu'à quatre, retenir le souffle le même temps, expirer sur quatre temps, retenir à nouveau quatre temps. Sans forcer, sans tension — la régularité fait tout. La concentration se porte sur le plexus solaire, le grand carrefour d'énergie du corps.",
      "La tradition distingue la méditation passive — celle-ci — des méditations actives, qui consistent en exercices de visualisation. Leur patron symbolique est Hermès, maître de tous les arts magiques, et sa baguette, le caducée : un bâton central où s'entrelacent deux serpents, souvent surmontés d'ailes. Les serpents figurent les principes binaires à l'œuvre dans l'univers — masculin et féminin, lumière et obscurité ; le bâton, l'axe entre Ciel et Terre ; les ailes, la conscience transcendante.",
      "Méditer, dans cette perspective, n'est pas fuir le monde : c'est s'asseoir au point d'équilibre des polarités — là précisément où, disent toutes les traditions de ce grimoire, aucune influence négative ne trouve prise.",
    ],
    note: "La pratique guidée complète vous attend dans l'onglet Rituels.",
  },
  {
    id: "mantras",
    titre: "Mantras : le pouvoir du Verbe",
    eyebrow: "Pratiques de l'esprit",
    resume: "« Au commencement était le Verbe » : les sons qui protègent, de l'AUM aux langues sacrées.",
    img: { id: "IMG-21", sujet: "Calligraphie du symbole AUM/OM à l'encre dorée, ou moine récitant, ambiance contemplative", src: "/images/img-21.jpg" },
    corps: [
      "« Au commencement était le Verbe, et le Verbe était Dieu. » Ce principe de la foi judéo-chrétienne a son équivalent exact dans la tradition hindoue : l'univers matériel — jagat, « ce qui se meut » — fut créé par la vibration divine. Toute chose, à son niveau le plus fondamental, est un assemblage de forces mouvantes ; l'atome le plus ténu vibre constamment et crée son propre son.",
      "Chaque chose possède ainsi sa signature sonore — son nom véritable ou « naturel ». Et ce concept est au cœur même de la magie : être capable de proférer le nom naturel d'une chose, c'est être à même d'entrer en relation avec elle. Voilà pourquoi, dans tant de traditions, le nom secret se garde jalousement — souvenez-vous du chapitre sur les talismans et du nom du pharaon.",
      "Tous les charmes et incantations reposent sur cette correspondance étroite entre certains mots et des forces spécifiques. Dans l'hindouisme et le bouddhisme, ces sons de pouvoir se nomment mantras. Le plus connu est le OM — plus exactement A-U-M — associé aux lettres du sanskrit, langage sacré ; l'hébreu jouit du même statut dans la tradition kabbaliste. Répété, le mantra du bouddhisme tibétain attire sur celui qui le prononce les bénédictions de la compassion.",
      "Nul besoin d'être moine pour en faire usage : un mot de sérénité, répété avec régularité sur le rythme de la respiration, apaise l'esprit et — dans le langage de la tradition — renforce l'aura. C'est le principe même des phrases du Cocon doré.",
    ],
    note: "Les phrases du Cocon doré (« Je suis calme. Je suis protégé. ») fonctionnent exactement comme un mantra occidental : la répétition fait la force.",
  },
  {
    id: "magie-angelique",
    titre: "Magie angélique et talismans planétaires",
    eyebrow: "Pratiques de l'esprit",
    resume: "La Croix de Lumière, le cercle aux quatre archanges, les esprits des planètes.",
    img: { id: "IMG-22", sujet: "Gravure d'archange (Raphaël) style Renaissance, ou cercle magique tracé avec pentagrammes aux quatre directions", src: "/images/img-22.jpg" },
    corps: [
      "Au sommet de la tradition ésotérique occidentale, la magie angélique place la protection sous l'égide des archanges. Son exercice fondateur est la Croix de Lumière : un exercice kabbaliste très efficace pour renforcer l'aura et concentrer l'énergie, traditionnellement accompli avant tout travail rituel — on y fait descendre la lumière à travers le corps, dessinant en soi une croix rayonnante.",
      "Vient ensuite le cercle magique, la grande enceinte de protection. Debout, face à l'Est, l'opérateur trace dans l'air un pentagramme d'une ligne continue — en l'imaginant tracé d'une ligne de feu — puis en désigne le centre et invoque, d'une voix haute et confiante, l'archange Raphaël, prince de l'Est. Il se tourne alors vers le Sud, trace un nouveau pentagramme, et poursuit ainsi aux quatre directions, chacune gardée par son archange : le cercle refermé, rien de négatif n'y pénètre.",
      "La tradition des talismans planétaires prolonge cette science : à chaque planète, la kabbale associe un Esprit et une Intelligence aux noms hébreux précis — Nakhiel, Intelligence du Soleil ; Tiriel, Intelligence de Mercure ; et leurs pareils pour la Lune, Vénus, Mars, Jupiter et Saturne. Gravés sur le métal de la planète, au jour et à l'heure qui lui correspondent, ces noms font du talisman un condensé des forces célestes.",
      "Faut-il y croire pour pratiquer la Croix de Lumière ? La tradition répond avec sagesse : l'exercice agit d'abord sur celui qui l'accomplit — concentration, verticalité, sentiment de force tranquille. C'est déjà, en soi, une protection.",
    ],
    note: "La Croix de Lumière est guidée pas à pas dans l'onglet Rituels — c'est l'ouverture idéale avant tout autre rite de ce grimoire.",
  },
  {
    id: "couleurs-magie",
    titre: "Magie blanche, noire… et grise",
    eyebrow: "Traditions du monde",
    resume: "La couleur de la magie est celle de l'intention.",
    img: { id: "IMG-23", sujet: "Deux bougies, une blanche une noire, flammes jumelles sur fond neutre — dualité élégante", src: "/images/img-23.jpg" },
    corps: [
      "La magie noire utilise des forces destructrices pour nuire ; la magie blanche emploie des forces harmonieuses pour servir la lumière. Mais la tradition ajoute aussitôt la vraie clé : la couleur de la magie est celle de l'intention de celui qui la pratique.",
      "Et la nature humaine étant ce qu'elle est, la plus grande partie de l'art tend ainsi à être « grise » : beaucoup de gens usent de ces pratiques à des fins personnelles — protection, chance, amour — sans malveillance ; d'autres obéissent à des motifs égoïstes ou malveillants. Le geste peut être identique ; l'intention fait tout.",
      "C'est la leçon que ce grimoire répète depuis son premier chapitre : le rite de l'huile, le sel, l'encens, le pentacle ne sont ni bons ni mauvais en eux-mêmes — ils amplifient ce que porte le cœur de qui les emploie. La tradition y ajoute sa loi de police : le coup en retour. Toute intention noire finit par revenir à son expéditeur.",
      "L'histoire a aussi croisé ces questions avec celle des sociétés initiatiques — rosicrucisme, franc-maçonnerie — aux idéaux profonds, mais dont le prestige fut parfois usurpé par des groupes ou des individus mal intentionnés. La règle des anciens vaut ici encore : jugez l'arbre à ses fruits, et l'opérateur à ses intentions.",
    ],
    note: "Employez tout ce grimoire en blanc : protection, apaisement, réconciliation. Le reste, la tradition le déconseille — et le coup en retour s'en charge.",
  },
  {
    id: "vaudou",
    titre: "Le Vaudou, religion des ancêtres",
    eyebrow: "Traditions du monde",
    resume: "D'Afrique de l'Ouest à Haïti et La Nouvelle-Orléans : une spiritualité réprimée mais jamais exterminée.",
    img: { id: "IMG-24", sujet: "Vévé vaudou tracé (motif géométrique rituel) ou scène de cérémonie haïtienne digne, tambours, sans cliché horrifique", src: "/images/img-24.jpg" },
    corps: [
      "Le Vaudou est une religion afro-antillaise apparue en Haïti, dans la partie occidentale de l'île d'Hispaniola. Entre 1510 et 1830, quelque trois millions d'esclaves originaires de l'Afrique occidentale furent amenés à Haïti : ceux qui s'échappèrent des plantations emportèrent avec eux leurs dieux et leurs rites, qui se mêlèrent au catholicisme imposé. Au XIXᵉ siècle, la religion migra aux États-Unis via La Nouvelle-Orléans.",
      "Réprimée mais jamais exterminée, elle survit aujourd'hui et connaît, au cours des dernières années, une popularité croissante. Loin des caricatures du cinéma, c'est une religion des ancêtres et des esprits — les lwa — servis par des prêtres et prêtresses qui sont aussi guérisseurs : ils prescrivent des remèdes végétaux, et la feuille de palmier compte parmi leurs symboles protecteurs, qui préservent leurs serviteurs pendant la possession rituelle — laquelle est, dans ce cadre, un acte sacré et non une affliction.",
      "Parmi les grandes figures : Erzili, esprit de l'éternel féminin, de l'amour et de la beauté — preuve s'il en fallait que ce panthéon parle d'abord de la vie, de la protection et de la douceur.",
      "Pourquoi ce chapitre dans un grimoire des protections ? Parce que le Vaudou est l'exemple le plus poignant de ce que ce grimoire raconte depuis le début : face à l'adversité la plus totale, les hommes ont toujours forgé des protections spirituelles — et les ont transmises. Le respecter, c'est respecter toutes les traditions réunies ici.",
    ],
    note: "Les « poupées vaudou » perçant de malheur appartiennent surtout au folklore hollywoodien — la magie des simulacres, elle, est universelle : nous l'avons croisée dans les chapitres sur les sortilèges et leur neutralisation.",
  },
  {
    id: "wicca",
    titre: "Wicca et vieux paganisme",
    eyebrow: "Traditions du monde",
    resume: "La religion païenne du XXᵉ siècle — à ne pas confondre avec la sorcellerie des grimoires.",
    img: { id: "IMG-25", sujet: "Autel wiccan sobre : pentacle de bois, bougies, fleurs de saison, croissant de lune — esthétique naturelle", src: "/images/img-25.jpg" },
    corps: [
      "Il ne faut pas confondre la sorcellerie des vieux grimoires avec la Wicca, qui est un phénomène du XXᵉ siècle : une religion païenne moderne, puisant dans le paganisme européen, la magie naturelle et le folklore britannique.",
      "La Wicca célèbre les cycles de la nature — la roue de l'année et ses huit fêtes, dont plusieurs recoupent nos vieilles célébrations françaises : le solstice d'été de la Saint-Jean, que nous avons rencontré au chapitre des plantes, en est l'exemple parfait. Ses pratiquants honorent une dualité divine, travaillent en cercle — la même enceinte protectrice que dans toute la tradition occidentale — et suivent une éthique simple : ne nuire à personne.",
      "Pour le lecteur de ce grimoire, la Wicca est intéressante comme miroir moderne : on y retrouve, réorganisés, presque tous les éléments du répertoire ancestral — le sel et l'eau consacrés, les bougies, l'encens, le pentacle, les amulettes chargées, les herbes de protection. Preuve que ce patrimoine n'est pas un musée : il continue de vivre, de se transmettre et de se réinventer.",
      "Comme toujours, la tradition invite au discernement : entre spiritualité sincère et folklore commercial, jugez à l'intention — c'est la leçon du chapitre sur les couleurs de la magie.",
    ],
    note: "La roue de l'année wiccane et notre calendrier populaire se répondent : Saint-Jean et solstice d'été, Chandeleur et Imbolc, Toussaint et Samhain.",
  },
  {
    id: "dictionnaire",
    titre: "Petit dictionnaire des superstitions",
    eyebrow: "Traditions du monde",
    resume: "Le sel qu'on ne prête pas, les cornes dans le dos, le V de la victoire : florilège.",
    img: { id: "IMG-26", sujet: "Composition d'objets superstitieux : salière renversée, échelle miniature, chat, miroir, trèfle, parapluie", src: "/images/img-26.jpg" },
    corps: [
      "Le sel ne se prête jamais. Pour être sûr d'éviter toutes sortes de désagréments, dit la tradition, on ne prête jamais de sel — le sel est protection, et prêter sa protection, c'est s'en défaire. On peut en donner, jamais en prêter : le don ne crée pas de lien de retour.",
      "Les cornes du diable. Faire les cornes dans le dos de quelqu'un — index et auriculaire tendus — attire la chance à celui qui fait le geste et détourne le mauvais œil : c'est le geste apotropaïque par excellence de l'Italie du Sud, cousin de la corne-amulette du rétroviseur. Porter sur soi une corne d'animal — en guise de blague à tabac, par exemple — protège lors des mauvaises rencontres.",
      "Le V de la victoire. Le fameux « V » rendu célèbre par Winston Churchill tient son origine, dit-on, d'un vieux geste de conjuration : doigts écartés, il fend et disperse les influences hostiles. La victoire commence par la protection.",
      "Les oiseaux messagers. La tradition prête à certains oiseaux le rôle d'augures : le chant répété d'un oiseau de mauvais augure près d'une maison où repose un malade était redouté comme une annonce — croyance bretonne entre autres. À l'inverse, l'oiseau doté d'une longévité exceptionnelle porte bonheur à qui le voit. Comme toujours, l'oiseau n'y est pour rien : c'est l'homme qui lit le ciel.",
      "Et notre florilège pourrait continuer sur des pages : la blouse déposée sur le tas de fumier pour renvoyer le mal à une ennemie — magie de correspondance dans toute sa rusticité —, le parapluie qu'on n'ouvre pas à l'intérieur, l'échelle qu'on ne passe pas dessous, le pain qu'on ne pose pas à l'envers. Chaque entrée de ce dictionnaire est un petit fossile de la grande peur ancestrale — et du grand art de la conjurer.",
    ],
    note: "Ce dictionnaire s'enrichira au fil des mises à jour de votre grimoire : chaque édition apportera sa moisson d'entrées nouvelles.",
  },
  {
    id: "art-talisman",
    titre: "L'art de fabriquer son talisman",
    eyebrow: "Objets de pouvoir",
    resume: "Les cinq types hermétiques, les supports, les sacs médecine et les plantes protectrices.",
    img: { id: "IMG-28", sujet: "Établi d'artisan ésotérique : disque de bois, feuille d'or, plume, encre, sceaux planétaires dessinés", src: "/images/img-28.jpg" },
    corps: [
      "Il y a une différence entre talisman et amulette : l'amulette est un objet porté pour la protection, tandis que le talisman peut être chargé magiquement à n'importe quelle fin, et n'a pas besoin d'être porté pour agir. Sa fonction principale, disent les textes, est de projeter la volonté sur le tissu souple de l'univers — et les détails de préparation comptent moins que la qualité de concentration qu'ils permettent d'atteindre. Les rituels de magie sympathique servent précisément à cela : s'harmoniser aux énergies avec lesquelles on veut travailler.",
      "Originellement, les talismans étaient gravés dans le métal ou la pierre ; plus tard, le parchemin puis le papier devinrent en Occident les supports favoris. La magie hermétique en distingue cinq types principaux : le talisman astrologique, portant les symboles des planètes ou des signes ; le talisman magique, portant sceaux, mots occultes et noms des anges ; le talisman mixte, qui combine les deux ; les sigilla planetarum, sceaux des planètes accompagnés de leurs symboles ; et le talisman hébreu, où les noms des anges planétaires s'inscrivent en lettres hébraïques — car l'hébreu, s'écrivant de droite à gauche, donne à chaque lettre une valeur numérique : les noms y sont aussi des nombres, et ces correspondances servent à tracer les sceaux planétaires et angéliques.",
      "Pour la défense psychique, les planètes qui conviennent sont Vénus et le Soleil. Le Soleil, corps cosmique de lumière, de conscience et de vitalité, est idéal pour les talismans protecteurs : la tradition décrit un disque en noyer ou en frêne, doré à l'or — le métal solaire. Pour un talisman plus personnel, on choisit la planète gouvernante de son signe et l'on adapte les correspondances — c'est tout l'objet de l'Atelier de l'Almanach.",
      "Les amulettes, elles, sont plus efficaces portées en permanence — cou, poignets, chevilles. Les sacs médecine des Indiens d'Amérique sont parfaits pour cela : un morceau de votre étoffe préférée, soie ou cuir, l'amulette au centre, l'étoffe tirée autour et nouée d'une ficelle en petite bourse. Fait avec soin, le sac opère lui-même comme une amulette.",
      "On y glisse volontiers des plantes protectrices, utilisées depuis l'Antiquité : l'ail — frais pour empêcher les mauvais esprits d'entrer, en têtes entières suspendues aux fenêtres pour protéger la demeure ; le houx, dont une branche fournit une protection générale ; le ginseng, dont la racine se brûle en Chine pour briser les sorts ; l'iris dans l'eau du bain ; les haricots dans des hochets pour faire partir les esprits mineurs.",
    ],
    note: "L'Atelier du talisman, dans l'Almanach, vous guide de l'intention jusqu'à l'heure planétaire exacte de fabrication — puis le rituel de consécration achève l'œuvre.",
  },
];

/* ============================================================
   LES RITUELS — pratiques guidées
   ============================================================ */
const RITUELS = [
  {
    id: "cocon",
    titre: "Le Cocon doré",
    duree: "10 minutes",
    intro: "La protection maîtresse du répertoire : l'enveloppe de lumière que rien de négatif ne traverse.",
    etapes: [
      "Installez-vous confortablement, dos droit, épaules relâchées. Fermez doucement les yeux.",
      "Respirez profondément trois fois, en laissant chaque expiration emporter les tensions du jour.",
      "Imaginez au-dessus de votre tête une sphère de lumière dorée, chaude et rayonnante comme un soleil de fin d'après-midi.",
      "Laissez cette lumière descendre lentement le long de votre corps : le visage, les épaules, la poitrine, le ventre, les jambes, jusqu'aux pieds.",
      "La lumière se referme sous vos pieds : vous êtes désormais enveloppé d'un cocon doré, souple, tiède, impénétrable.",
      "Répétez intérieurement, trois fois, lentement : « Je suis calme. Je suis fort. Je suis protégé. Rien de négatif ne me traverse. »",
      "Sentez que le cocon reste avec vous. Rouvrez les yeux en gardant la sensation de chaleur : la protection vous accompagne.",
    ],
  },
  {
    id: "cocon-rapide",
    titre: "Le bouclier rapide",
    duree: "1 minute",
    intro: "Version d'urgence du Cocon doré : avant une rencontre difficile, dans les transports, n'importe où. Protège environ une heure.",
    etapes: [
      "Où que vous soyez, prenez une seule grande inspiration, lente et profonde.",
      "En expirant, visualisez d'un seul geste la lumière dorée qui jaillit au-dessus de vous et vous enveloppe entièrement, en un éclair.",
      "Serrez brièvement les poings, pouces à l'intérieur des paumes : le circuit est fermé.",
      "Dites-vous intérieurement, une fois, avec fermeté : « Protégé. »",
      "Relâchez les mains, reprenez votre activité. Le bouclier tient environ une heure ; renouvelez-le si nécessaire.",
    ],
  },
  {
    id: "huile",
    titre: "Le rite de l'huile",
    duree: "15 minutes",
    intro: "L'épreuve ancestrale de vérification, encore pratiquée dans toute la Méditerranée. À la tombée du jour, dans le calme.",
    etapes: [
      "Réunissez : un petit bassin ou saladier d'eau, une soucoupe, de l'huile d'olive, une bougie blanche, une allumette en bois.",
      "Versez trois cuillerées d'huile d'olive dans la soucoupe.",
      "Allumez la bougie blanche avec l'allumette en bois, puis éteignez toute autre lumière.",
      "Si le rite concerne une personne présente, passez trois fois la soucoupe au-dessus de sa tête.",
      "Trempez l'index gauche dans l'huile et laissez tomber trois gouttes dans l'eau.",
      "Observez : les gouttes restent-elles concentrées, bien rondes ? La tradition dit que tout va bien. S'étalent-elles en cercles concentriques ? La tradition y lit une influence — d'autant plus forte que les cercles s'étendent.",
      "Dans ce cas, ne vous alarmez pas : enchaînez avec la purification à l'encens et le Cocon doré. La tradition est formelle : les influences repérées sont, neuf fois sur dix, de simples pensées négatives que ces pratiques dissipent.",
    ],
  },
  {
    id: "sel-rite",
    titre: "Le rite du sel",
    duree: "10 minutes",
    intro: "Sonder une maison par le sel et la flamme, selon l'ancienne recette des 27 grains.",
    etapes: [
      "Réunissez : un récipient en cuivre ou en terre cuite, du gros sel, de l'alcool à brûler, une allumette en bois. Opérez sur une surface résistante à la chaleur, loin de tout ce qui peut prendre feu.",
      "Comptez 27 grains de gros sel — trois fois trois fois trois, le chiffre parfait porté à sa puissance — et déposez-les dans le récipient.",
      "Versez dessus 7 cuillerées d'alcool.",
      "Enflammez avec l'allumette en bois et reculez d'un pas.",
      "Écoutez : si le sel brûle en silence, la maison est paisible. S'il crépite, la tradition y entend des négativités — d'autant plus présentes que les crépitements sont bruyants.",
      "Laissez tout se consumer et refroidir complètement. Jetez les résidus hors de la maison.",
      "En cas de crépitements : enchaînez avec la purification complète du foyer, ci-dessous.",
    ],
  },
  {
    id: "encens",
    titre: "La purification du foyer",
    duree: "20 minutes",
    intro: "Le grand rituel de l'encens : chaque ouverture de la maison, du seuil aux fenêtres. Fenêtres entrouvertes, prudence avec la flamme.",
    etapes: [
      "Choisissez de l'encens pur : 7 ou 9 grains, 3 pincées de poudre, ou des bâtonnets en nombre impair — l'impair marque l'accomplissement.",
      "Allumez avec une allumette en bois — jamais autrement, dit la tradition.",
      "Commencez devant l'entrée principale : présentez la fumée au seuil, en formulant votre volonté d'apaiser ce foyer.",
      "Passez lentement devant chaque ouverture : portes, fenêtres, en laissant la fumée dessiner ses volutes devant chacune.",
      "Observez la fumée : blanche et légère, tout va bien ; sombre, la tradition y lit des négativités qui se dissipent précisément par cette combustion — continuez jusqu'à ce qu'elle blanchisse.",
      "Terminez au centre de la pièce principale, en pensant à ceux qui vivent ici.",
      "Conservez l'encens brûlé dans un flacon de verre fumé, placé sur le balcon ou le rebord d'une fenêtre. Aérez largement.",
    ],
  },
  {
    id: "bougies",
    titre: "Les neuf bougies",
    duree: "9 jours",
    intro: "La neuvaine de lumière : trois croix, neuf flammes, pour dissiper les influences tenaces du foyer.",
    etapes: [
      "Procurez-vous neuf bougies. Sur chacune, gravez ou tracez trois croix.",
      "Le premier jour, allumez trois bougies (avec une allumette en bois) et laissez-les brûler sous surveillance, dans la pièce principale.",
      "Chaque jour suivant, ajoutez une bougie allumée aux précédentes.",
      "Au neuvième jour, les neuf bougies brûlent ensemble : la neuvaine est accomplie.",
      "Pendant ces neuf jours, gardez si possible la maison rangée et aérée — la lumière travaille mieux dans un espace clair.",
      "Ne laissez jamais les flammes sans surveillance ; éteignez-les en quittant la pièce et rallumez-les à votre retour, cela ne rompt pas le rite.",
    ],
  },
  {
    id: "brosse",
    titre: "Le grand ménage symbolique",
    duree: "45 minutes",
    intro: "Un mardi ou un samedi, en lune décroissante : quand la lune diminue, ce qu'on chasse diminue avec elle.",
    etapes: [
      "Consultez le calendrier lunaire : choisissez un mardi ou un samedi en période de lune décroissante.",
      "Munissez-vous d'une brosse ou d'un balai — idéalement réservé à cet usage.",
      "Brossez chaque pièce, des recoins vers la porte, en pensant intensément déloger toute influence négative. La pensée est l'outil ; la brosse, son prolongement.",
      "Poussez symboliquement le tout vers l'extérieur, par la porte d'entrée, et au-delà du seuil.",
      "Placez la brosse derrière la porte d'entrée : elle y montera la garde contre les influences. Jamais devant la porte — ce serait offenser vos visiteurs.",
      "Terminez par une coupelle de gros sel posée dans la pièce principale, à renouveler régulièrement.",
    ],
  },
  {
    id: "fleur",
    titre: "Les neuf fleurs",
    duree: "9 jours",
    intro: "La contre-mesure la plus élégante du répertoire : répondre au mal par un geste d'amitié, neuf jours durant.",
    etapes: [
      "Identifiez la personne dont vous pensez que la rancœur ou la jalousie pèse sur vous — souvent, disait la tradition, dans le cercle familial même.",
      "Chaque jour pendant neuf jours, envoyez-lui ou offrez-lui une fleur.",
      "La condition absolue : la sincérité. Envoyée sans amitié réelle, la fleur n'est qu'une fleur. La tradition est catégorique : le geste ne fonctionne que porté par une bienveillance authentique.",
      "Si la fleur réelle est impossible, la tradition admet la fleur pensée : chaque jour, formulez pour cette personne un vœu de bien sincère.",
      "Pendant ces neuf jours, si vous croisez la personne : soyez d'une gentillesse parfaite. Le trouble que cela sème chez qui vous voulait du mal vaut toutes les barrières.",
      "Au neuvième jour, observez ce qui a changé — autour de vous, et en vous.",
    ],
  },
  {
    id: "croix-lumiere",
    titre: "La Croix de Lumière",
    duree: "5 minutes",
    intro: "L'exercice kabbaliste qui renforce l'aura et concentre l'énergie. À accomplir avant tout autre rite de ce grimoire.",
    etapes: [
      "Tenez-vous debout, pieds joints, dos droit, bras le long du corps. Respirez calmement.",
      "Imaginez, très haut au-dessus de votre tête, une sphère de lumière blanche éclatante — la source.",
      "Faites descendre un rayon de cette lumière à travers le sommet de votre crâne, le long de votre colonne, jusque sous vos pieds : l'axe vertical de la croix est tracé en vous.",
      "Portez votre attention à votre épaule droite, puis faites courir la lumière d'une épaule à l'autre, en traversant la poitrine : la branche horizontale est tracée.",
      "Contemplez un instant cette croix de lumière rayonnant en vous, du ciel à la terre et d'une main à l'autre : vous êtes le carrefour de la lumière.",
      "Croisez les mains sur la poitrine et laissez la lumière s'étendre autour de vous en une sphère : l'aura est renforcée, l'énergie concentrée.",
      "Vous pouvez enchaîner directement avec le rite de votre choix — c'est l'ouverture traditionnelle de tout travail rituel.",
    ],
  },
  {
    id: "pharaon",
    titre: "La méditation du Pharaon",
    duree: "10 minutes",
    intro: "La posture du Dieu égyptien et le souffle carré : l'assise royale qui équilibre l'être intérieur.",
    etapes: [
      "Asseyez-vous sur une chaise au dossier droit ou un tabouret : le dos droit, les pieds à plat sur le sol, les paumes posées sur les cuisses — la posture exacte des statues assises d'Égypte.",
      "Fermez les yeux. Sans forcer la respiration, inspirez lentement et sans heurt en comptant jusqu'à quatre.",
      "Retenez votre souffle le même temps — quatre temps, sans tension.",
      "Expirez de même en comptant jusqu'à quatre, puis retenez poumons vides pendant quatre temps. Ce carré constitue un cycle respiratoire complet.",
      "Continuez de respirer en observant ces cycles, tandis que votre concentration se pose doucement sur le plexus solaire — le grand carrefour d'énergie du corps.",
      "Si une pensée survient, laissez-la passer comme un nuage et revenez au compte du souffle.",
      "Après une dizaine de minutes, laissez la respiration redevenir libre, rouvrez les yeux, et emportez la stabilité du Pharaon dans votre journée.",
    ],
  },
  {
    id: "charger",
    titre: "Charger une amulette",
    duree: "10 minutes",
    intro: "Cristal, pierre percée, bijou ou objet personnel : l'énergétiser pour éveiller ses pouvoirs protecteurs.",
    etapes: [
      "Choisissez votre amulette : un cristal — le quartz fumé est le grand protecteur traditionnel, le quartz clair se prête à toute intention —, une pierre qui vous a choisi, un bijou personnel. Évitez les matières artificielles comme le plastique, très difficiles à charger.",
      "Si c'est une pierre ou un cristal, nettoyez-le d'abord à l'eau courante — l'eau vive d'un ruisseau est l'idéal.",
      "Tenez l'amulette dans votre main réceptive : la gauche si vous êtes droitier, la droite si vous êtes gaucher.",
      "Prenez quelques respirations profondes, puis régularisez votre souffle sur un rythme calme.",
      "Imaginez que vous convoquez votre lumière intérieure : sentez-la vibrer au rythme de votre cœur, puis descendre le long du bras jusqu'à la main qui tient l'objet.",
      "Visualisez l'amulette qui s'emplit de cette lumière et devient elle-même rayonnante, tandis que vous formulez clairement son office : « Protège-moi. »",
      "C'est fait : utilisez votre amulette immédiatement de la manière choisie — poche, pendentif, seuil de la maison. Une amulette bien chargée n'a besoin d'être rechargée qu'une ou deux fois l'an, au plus.",
    ],
  },
  {
    id: "eau-salee",
    titre: "Le bouclier d'eau salée",
    duree: "40 minutes",
    intro: "Laver, exposer, encercler : la triple purification du foyer par l'alliance du sel et de l'eau.",
    etapes: [
      "Préparez une eau salée fraîche : de l'eau claire, une bonne poignée de gros sel, dissoute en tournant dans le sens du soleil.",
      "Lavez les sols de la maison avec cette eau — et, si le cœur vous en dit, passez un linge humide sur les murs : une couche fraîche d'eau salée assainit l'atmosphère entière d'une pièce, dit la tradition.",
      "Disposez ensuite des bols d'eau claire dans les pièces de vie : exposée, l'eau capte silencieusement les influences ambiantes. On peut y ajouter quelques grains de sel pour la renforcer.",
      "Placez un bol sous le lit pour la protection des nuits.",
      "Renouvelez l'eau des bols régulièrement — chaque semaine par exemple — en la jetant toujours hors de la maison.",
      "Pour une protection renforcée d'un lieu ou d'un objet précieux, versez un fin cercle de sel autour de lui : la plus ancienne enceinte protectrice du monde.",
      "Terminez en nettoyant à l'eau courante les cristaux et objets protecteurs de la maison : eux aussi se déchargent avec le temps, et l'eau vive les rend à leur office.",
    ],
  },
  {
    id: "exercices-corps",
    titre: "Les exercices du corps subtil",
    duree: "10 minutes",
    intro: "Deux postures traditionnelles d'autodéfense psychique pour renforcer le corps éthérique et sceller l'énergie.",
    etapes: [
      "Première posture — l'accroupi scellé : pieds écartés d'une largeur d'épaules, orteils vers l'avant, accroupissez-vous.",
      "Joignez vos mains et placez vos coudes à l'intérieur de vos genoux.",
      "Montez sur la pointe des pieds, mains positionnées vers l'avant, regard droit devant vous.",
      "Respirez lentement et profondément, et gardez la position aussi longtemps que vous le pouvez — le circuit énergétique est fermé, l'énergie se concentre.",
      "Seconde posture — l'appui du cœur : allongez-vous sur le ventre. Joignez vos mains sous votre plexus solaire, paumes à plat sur le sol, pouces et index se touchant, de sorte que l'espace entre les mains dessine la forme d'un cœur.",
      "Poussez vers le haut jusqu'à ce que vos bras soient verticaux, tout votre corps soutenu sur mains et orteils, orteils pointant vers l'arrière.",
      "Tenez en respirant calmement, puis redescendez doucement. Le cœur dessiné sous le plexus solaire place tout l'exercice sous le signe de la plus haute des énergies protectrices.",
    ],
  },
  {
    id: "consacrer",
    titre: "Consacrer un talisman",
    duree: "20 minutes",
    intro: "Le rituel des quatre éléments qui unit le talisman à la volonté de son créateur. À accomplir après la fabrication, idéalement précédé de la Croix de Lumière.",
    etapes: [
      "Préparez sur votre table : votre talisman fabriqué, de l'encens, un bol d'eau (bénite ou salée), quelques grains de sel gemme, une bougie et une allumette en bois. Ouvrez si possible une fenêtre vers l'Est.",
      "Accomplissez d'abord la Croix de Lumière — c'est l'ouverture traditionnelle qui concentre l'énergie du rituel.",
      "L'Air — tournez-vous vers l'Est et allumez l'encens. Tenez le talisman au-dessus de la fumée et dites : « Par le Serpent d'Airain, devant lequel sont tombés les serpents de feu, sois pour moi un signe de lumière et un sceau de volonté, m'accordant ta protection. »",
      "Le Feu — passez brièvement le talisman au-dessus de la flamme de la bougie (sans le brûler), en visualisant la lumière qui le pénètre. S'il s'agit d'un talisman solaire, le mieux est de l'exposer ensuite aux rayons du Soleil.",
      "L'Eau — tournez-vous vers l'Ouest et aspergez le talisman de quelques gouttes d'eau, en disant : « Au nom d'Elohim, et par l'esprit des eaux vivantes, sois pour moi un signe de lumière et un sceau de volonté, m'accordant ta protection. »",
      "La Terre — déposez quelques grains de sel gemme sur le talisman et dites : « Par le sel de la terre et par la vertu de la vie éternelle, sois pour moi un signe de lumière et un sceau de volonté, m'accordant ta protection. »",
      "Tenez enfin le talisman entre vos deux mains, formulez une dernière fois son office avec une totale concentration — la qualité de la concentration fait tout, disent les textes — puis rangez-le ou portez-le selon sa destination. Le talisman est consacré.",
    ],
  },
];

/* ============================================================
   L'ALMANACH — correspondances traditionnelles de protection
   ============================================================ */
const ZODIAQUE = [
  { signe: "Bélier", dates: "21 mars – 20 avril", nombres: "1 et 6", metal: "Fer", couleur: "Rouge feu", animal: "Chat noir", fleur: "Lavande", parfums: "Absinthe, basilic, poivre", pierres: ["Rubis", "Améthyste"] },
  { signe: "Taureau", dates: "21 avril – 20 mai", nombres: "2 et 9", metal: "Cuivre", couleur: "Vert foncé", animal: "Chien", fleur: "Rose rouge de Provins", parfums: "Rose, mélisse, gingembre", pierres: ["Saphir", "Zircon"] },
  { signe: "Gémeaux", dates: "21 mai – 21 juin", nombres: "3 et 5", metal: "Argent", couleur: "Marron", animal: "Lapin", fleur: "Origan", parfums: "Vanille, acacia, menthe", pierres: ["Agate", "Aigue-marine"] },
  { signe: "Cancer", dates: "22 juin – 22 juillet", nombres: "4 et 7", metal: "Argent", couleur: "Blanc", animal: "Poisson", fleur: "Lilas", parfums: "Tilleul, ambre, santal", pierres: ["Perle", "Émeraude"] },
  { signe: "Lion", dates: "23 juillet – 22 août", nombres: "5 et 7", metal: "Or", couleur: "Or", animal: "Écureuil", fleur: "Tournesol", parfums: "Angélique, baume, encens, cyclamen", pierres: ["Brillant", "Topaze"] },
  { signe: "Vierge", dates: "23 août – 22 septembre", nombres: "5, 6 et 7", metal: "Mercure", couleur: "Multicolore", animal: "Singe", fleur: "Jacinthe", parfums: "Gardénia, acacia, mille-feuille", pierres: ["Jade", "Cornaline"] },
  { signe: "Balance", dates: "23 septembre – 22 octobre", nombres: "7", metal: "Cuivre", couleur: "Vert pâle", animal: "Chat", fleur: "Verveine", parfums: "Iris, mousse", pierres: ["Diamant", "Lapis-lazuli"] },
  { signe: "Scorpion", dates: "23 octobre – 21 novembre", nombres: "8 et 9", metal: "Fer", couleur: "Rouge vermeil", animal: "Mouton", fleur: "Bruyère", parfums: "Tubéreuse, genêt, verveine, citronnelle", pierres: ["Rubis", "Topaze"] },
  { signe: "Sagittaire", dates: "22 novembre – 20 décembre", nombres: "3 et 9", metal: "Étain", couleur: "Bleu ciel", animal: "Tortue", fleur: "Violette", parfums: "Amarante, freesia, calycanthe", pierres: ["Turquoise", "Grenat"] },
  { signe: "Capricorne", dates: "21 décembre – 19 janvier", nombres: "8 et 10", metal: "Plomb", couleur: "Marron et gris", animal: "Oiseaux (tous)", fleur: "Chèvrefeuille", parfums: "Narcisse, jacinthe, menthe sauvage", pierres: ["Onyx", "Chrysolithe"] },
  { signe: "Verseau", dates: "20 janvier – 18 février", nombres: "4 et 11", metal: "Plomb", couleur: "Bleu et gris", animal: "Perroquet", fleur: "Fougère", parfums: "Muguet, dracontium, réséda", pierres: ["Grenat", "Saphir"] },
  { signe: "Poissons", dates: "19 février – 20 mars", nombres: "5 et 12", metal: "Or blanc", couleur: "Bleu marine", animal: "Perruche", fleur: "Glycine", parfums: "Jasmin, pivoine, fleur d'oranger", pierres: ["Corail", "Aigue-marine"] },
];

const PIERRES = [
  { nom: "Turquoise", vertu: "« Pierre de la santé » des Arabes, portée en talisman sur le front. Protège du mauvais œil et des esprits malins — la protectrice par excellence." },
  { nom: "Émeraude", vertu: "Symbole d'harmonie, d'amitié, de sincérité et de fidélité. Protège du mauvais œil, renforce la vue, développe la mémoire, porte bonheur." },
  { nom: "Quartz fumé", vertu: "Le grand protecteur de la tradition des cristaux — la pierre à choisir quand on veut une amulette de protection sans hésiter." },
  { nom: "Quartz clair", vertu: "Si réceptif qu'il se prête immédiatement à n'importe quelle intention quand on le charge. La pierre universelle du débutant." },
  { nom: "Corail", vertu: "Donne la prudence, préserve des épidémies, aide les enfants à grandir en bonne santé, protège des dangers de la mer. L'amulette des berceaux depuis l'Antiquité romaine." },
  { nom: "Améthyste", vertu: "Sert contre les névralgies, fortifie la mémoire, donne une bonne faculté de jugement, éloigne l'ivresse et porte chance en amour." },
  { nom: "Topaze rose", vertu: "Renforce le système nerveux, aide à surmonter les complexes et attire la sympathie." },
  { nom: "Saphir", vertu: "Porté au front : calme les inflammations, préserve des douleurs de tête et des névroses, porte chance." },
  { nom: "Rubis", vertu: "Préserve des contagions, guérit les mélancolies, conserve la jeunesse à qui le porte." },
  { nom: "Jaspe", vertu: "Protège la vue, soutient la digestion, préserve des contagions et des poisons." },
  { nom: "Diamant", vertu: "Sauvegarde des ennemis, éloigne les dangers des femmes qui accouchent." },
  { nom: "Grenat", vertu: "Conserve la santé et protège en voyage — la pierre des routes." },
  { nom: "Ambre", vertu: "Renforce le cœur et le cerveau." },
  { nom: "Jade", vertu: "Veille sur les yeux et les reins ; pierre d'équilibre des traditions d'Orient." },
];

const FUMIGATIONS = [
  { nom: "Encens pur", usage: "Le roi des fumigations : chasse les mauvaises pensées, éloigne les forces négatives, protège l'esprit. Pour purifier : devant l'entrée et chaque ouverture. En grains : 7 ou 9. En poudre : 3 pincées. En bâtonnets : toujours un nombre impair. Toujours allumé avec une allumette en bois." },
  { nom: "Myrrhe", usage: "La sœur de l'encens, qui agit sur le corps : éloigne les tentations, protège des sortilèges d'amour et des infections. S'unit à l'encens dans les fumigations profondes du foyer." },
  { nom: "Encens + myrrhe portés sur soi", usage: "Trois grains de chaque, portés en permanence : le plus simple et le plus puissant des talismans végétaux de la tradition." },
  { nom: "Le parfum magique de votre signe", usage: "Chaque signe zodiacal possède ses parfums propres (voir votre profil ci-dessus) : les brûler ou les porter accorde vos protections à votre nature profonde." },
];

/* ============================================================
   L'ATELIER DU TALISMAN — planètes, heures magiques, confection
   Méthode des heures planétaires : ordre chaldéen, d'après la
   tradition et le calculateur Tempus Magis (tempus-magis.fr).
   ============================================================ */
const PLANETES = {
  Soleil:  { symbole: "\u2609", jour: "Dimanche", metal: "Or", couleur: "Or / jaune", encens: "Encens, myrrhe, benjoin", esprit: "Sorath", intelligence: "Nakhiel", support: "Disque de noyer ou de fr\u00eane, dor\u00e9", plantes: "Ang\u00e9lique, encens, cyclamen, tournesol (par le Lion, signe du Soleil)", img: "SOL", teinte: "#E3C78A" },
  Lune:    { symbole: "\u263D", jour: "Lundi", metal: "Argent", couleur: "Blanc / argent", encens: "Santal, camphre", esprit: "Chasmoda\u00ef", intelligence: "Malka (tradition d'Agrippa)", support: "Plaque d'argent ou parchemin blanc", plantes: "Tilleul, santal, ambre, lilas (par le Cancer, signe de la Lune)", img: "LUN", teinte: "#C8D4E0" },
  Mars:    { symbole: "\u2642", jour: "Mardi", metal: "Fer", couleur: "Rouge", encens: "Poivre, basilic", esprit: "Barzabel (tradition d'Agrippa)", intelligence: "Graphiel (tradition d'Agrippa)", support: "Plaque de fer ou parchemin rouge", plantes: "Absinthe, basilic, poivre, lavande, bruy\u00e8re (par le B\u00e9lier et le Scorpion)", img: "MAR", teinte: "#D98A7A" },
  Mercure: { symbole: "\u263F", jour: "Mercredi", metal: "Alliages (le vif-argent \u00e9tant proscrit)", couleur: "Multicolore / orang\u00e9", encens: "Menthe, acacia", esprit: "Taphthartharath (tradition d'Agrippa)", intelligence: "Tiriel", support: "Parchemin ou papier de qualit\u00e9", plantes: "Menthe, vanille, acacia, origan (par les G\u00e9meaux et la Vierge)", img: "MER", teinte: "#B8A9D9" },
  Jupiter: { symbole: "\u2643", jour: "Jeudi", metal: "\u00c9tain", couleur: "Bleu / pourpre", encens: "C\u00e8dre, safran", esprit: "Hisma\u00ebl (tradition d'Agrippa)", intelligence: "Iophiel (tradition d'Agrippa)", support: "Plaque d'\u00e9tain ou parchemin bleu", plantes: "Amarante, freesia, violette (par le Sagittaire)", img: "JUP", teinte: "#8FB4D9" },
  "V\u00e9nus": { symbole: "\u2640", jour: "Vendredi", metal: "Cuivre", couleur: "Vert", encens: "Rose, verveine", esprit: "Kedemel (tradition d'Agrippa)", intelligence: "Hagiel (tradition d'Agrippa)", support: "Plaque de cuivre ou parchemin vert", plantes: "Rose, verveine, m\u00e9lisse, iris (par le Taureau et la Balance)", img: "VEN", teinte: "#9BC9A3" },
  Saturne: { symbole: "\u2644", jour: "Samedi", metal: "Plomb", couleur: "Noir / gris sombre", encens: "Myrrhe, cypr\u00e8s", esprit: "Zazel (tradition d'Agrippa)", intelligence: "Agiel (tradition d'Agrippa)", support: "Plaque de plomb ou parchemin sombre", plantes: "Narcisse, ch\u00e8vrefeuille, foug\u00e8re, menthe sauvage (par le Capricorne et le Verseau)", img: "SAT", teinte: "#9A9AA8" },
};

const INTENTIONS = [
  { but: "Protection profonde \u00b7 bannir une influence", planete: "Saturne", detail: "Saturne gouverne les protections durables, les bannissements et tout ce qu'on souhaite faire cesser. \u00c0 marier avec la lune d\u00e9croissante." },
  { but: "Protection \u00b7 sant\u00e9 \u00b7 vitalit\u00e9", planete: "Soleil", detail: "Le Soleil, corps de lumi\u00e8re et de vitalit\u00e9, est id\u00e9al pour les talismans prot\u00e9geant la sant\u00e9 et le rayonnement personnel \u2014 le grand protecteur de la tradition." },
  { but: "Courage \u00b7 d\u00e9fense \u00b7 force", planete: "Mars", detail: "Mars galvanise la volont\u00e9, prot\u00e8ge dans les affrontements et brise les blocages. Le talisman de courage avant une \u00e9preuve." },
  { but: "Amour \u00b7 harmonie \u00b7 r\u00e9conciliation", planete: "V\u00e9nus", detail: "V\u00e9nus gouverne l'amour, la beaut\u00e9 et l'harmonie \u2014 et compte, avec le Soleil, parmi les plan\u00e8tes de la d\u00e9fense psychique." },
  { but: "Chance \u00b7 prosp\u00e9rit\u00e9 \u00b7 expansion", planete: "Jupiter", detail: "La grande b\u00e9n\u00e9fique : abondance, chance, justice et croissance. \u00c0 marier avec la lune croissante." },
  { but: "\u00c9tudes \u00b7 communication \u00b7 commerce", planete: "Mercure", detail: "Le messager des dieux : parole, \u00e9crits, examens, contrats et \u00e9changes." },
  { but: "Intuition \u00b7 r\u00eaves \u00b7 foyer \u00b7 voyages", planete: "Lune", detail: "La Lune r\u00e9git l'intuition, les r\u00eaves, la m\u00e9moire, le foyer et les cycles \u2014 la plan\u00e8te du monde int\u00e9rieur." },
];

/* Ordre chald\u00e9en et calcul des heures plan\u00e9taires (12 heures in\u00e9gales
   de jour du lever au coucher, 12 de nuit) \u2014 m\u00e9thode traditionnelle */
const ORDRE_CHALDEEN = ["Saturne", "Jupiter", "Mars", "Soleil", "V\u00e9nus", "Mercure", "Lune"];
const MAITRES_JOURS = ["Soleil", "Lune", "Mars", "Mercure", "Jupiter", "V\u00e9nus", "Saturne"]; // getDay() 0=dimanche
const NOMS_JOURS = ["dimanche", "lundi", "mardi", "mercredi", "jeudi", "vendredi", "samedi"];

function calculerHeures(lever, coucher, dateISO) {
  const [lh, lm] = lever.split(":").map(Number);
  const [ch, cm] = coucher.split(":").map(Number);
  const tLever = lh * 60 + lm, tCoucher = ch * 60 + cm;
  const d = dateISO ? new Date(dateISO + "T12:00:00") : new Date();
  const jour = d.getDay();
  const maitre = MAITRES_JOURS[jour];
  let idx = ORDRE_CHALDEEN.indexOf(maitre);
  const dureeJour = (tCoucher - tLever) / 12;
  const dureeNuit = (24 * 60 - (tCoucher - tLever)) / 12;
  const fmt = (mn) => {
    mn = ((mn % (24 * 60)) + 24 * 60) % (24 * 60);
    return String(Math.floor(mn / 60)).padStart(2, "0") + ":" + String(Math.round(mn % 60)).padStart(2, "0");
  };
  const heures = [];
  for (let i = 0; i < 12; i++) {
    heures.push({ n: i + 1, type: "jour", planete: ORDRE_CHALDEEN[idx % 7], debut: fmt(tLever + i * dureeJour), fin: fmt(tLever + (i + 1) * dureeJour) });
    idx++;
  }
  for (let i = 0; i < 12; i++) {
    heures.push({ n: i + 1, type: "nuit", planete: ORDRE_CHALDEEN[idx % 7], debut: fmt(tCoucher + i * dureeNuit), fin: fmt(tCoucher + (i + 1) * dureeNuit) });
    idx++;
  }
  return { heures, maitre, nomJour: NOMS_JOURS[jour] };
}

const CALENDRIER = [
  { quand: "Mardi ou samedi, en lune décroissante", quoi: "Les jours des grandes purifications : le grand ménage symbolique, le brossage de la maison. Quand la lune diminue, ce qu'on chasse diminue avec elle." },
  { quand: "Neuf jours de suite", quoi: "La durée sacrée des neuvaines : les neuf fleurs de la réconciliation, les neuf bougies marquées de trois croix. Le neuf, triple triade, est le nombre de l'accomplissement." },
  { quand: "La nuit de la Saint-Jean — 24 juin", quoi: "L'apogée de la magie des plantes : cette nuit-là, toutes possèdent des vertus qu'elles n'auront plus les autres jours. Entre 23 h et minuit, on taille la baguette de noisetier. Les herbes cueillies protègent la maison l'année entière." },
  { quand: "Avant Noël et Pâques", quoi: "Le temps traditionnel de la bénédiction et de la purification des maisons — la forme la plus haute du rituel du foyer." },
  { quand: "Les nombres impairs", quoi: "3, 5, 7, 9 : les nombres de l'accomplissement et de la perfection, à respecter dans tous les rites — grains d'encens, bougies, jours. Le pair marque l'attente ; l'impair, l'arrivée." },
];

/* ============================================================
   L'ÉCLAIRAGE — lecture des signes selon la tradition
   ============================================================ */
const SIGNES = [
  { s: "Fatigue inexpliquée, sommeil agité, esprit encombré", poids: 1 },
  { s: "Bâillements répétés en présence d'une personne précise", poids: 1 },
  { s: "Série de petits malheurs qui s'enchaînent sans logique", poids: 2 },
  { s: "Objets qui se cassent, projets qui échouent au dernier moment", poids: 2 },
  { s: "Tensions ou disputes qui éclatent de nulle part au foyer", poids: 2 },
  { s: "Sensation de malaise dans certaines pièces de la maison", poids: 2 },
  { s: "Une personne de l'entourage dont la jalousie est connue", poids: 2 },
  { s: "Rêves où apparaît une personne malveillante, ou avertissements en songe", poids: 2 },
  { s: "Marques ou formes étranges découvertes dans la maison, l'oreiller, le matelas", poids: 3 },
];

/* ============================================================
   COMPOSANTS D'INTERFACE
   ============================================================ */

function Eyebrow({ children, color = C.or }) {
  return (
    <div style={{
      fontFamily: "'Jost', sans-serif", fontWeight: 500, fontSize: 11,
      letterSpacing: "0.22em", textTransform: "uppercase", color, marginBottom: 8,
    }}>
      {children}
    </div>
  );
}

function Divider() {
  return (
    <div style={{ display: "flex", alignItems: "center", gap: 12, margin: "26px 0" }}>
      <div style={{ flex: 1, height: 1, background: C.ligne }} />
      <svg width="14" height="14" viewBox="0 0 14 14">
        <circle cx="7" cy="7" r="3" fill="none" stroke={C.or} strokeWidth="1" />
        <circle cx="7" cy="7" r="1.2" fill={C.or} />
      </svg>
      <div style={{ flex: 1, height: 1, background: C.ligne }} />
    </div>
  );
}

const boutonPrincipal = {
  display: "block", width: "100%", padding: "15px 20px", marginBottom: 12,
  background: `linear-gradient(135deg, ${C.or}, #A8843F)`, border: "none", borderRadius: 10,
  color: "#1A1408", fontFamily: "'Jost', sans-serif", fontWeight: 500, fontSize: 15,
  letterSpacing: "0.06em", cursor: "pointer",
};
const boutonSecondaire = {
  display: "block", width: "100%", padding: "14px 20px", marginBottom: 12,
  background: "transparent", border: `1px solid ${C.ligne}`, borderRadius: 10,
  color: C.parchemin, fontFamily: "'Jost', sans-serif", fontWeight: 400, fontSize: 15,
  letterSpacing: "0.06em", cursor: "pointer",
};
const boutonTexte = {
  display: "block", margin: "8px auto 0", padding: "10px",
  background: "none", border: "none", color: "#6B7690",
  fontFamily: "'Jost', sans-serif", fontSize: 13, cursor: "pointer", letterSpacing: "0.08em",
};
const titrePage = {
  fontFamily: "'Cormorant Garamond', serif", fontWeight: 500, fontSize: 30,
  color: C.parchemin, textAlign: "center", margin: "18px 0 10px", lineHeight: 1.2,
};
const texteCourant = {
  fontFamily: "'EB Garamond', serif", fontSize: 16, lineHeight: 1.7,
  color: C.parcheminDoux, margin: "0 0 16px",
};

/* ---------- Activation ---------- */
function Activation({ onActive }) {
  const [mode, setMode] = useState(null);
  const [code, setCode] = useState("");
  const [erreur, setErreur] = useState("");
  const [scan, setScan] = useState(false);

  const valider = (c) => {
    const propre = c.trim().toUpperCase();
    if (CODES_DEMO.includes(propre)) {
      onActive({ code: propre });
    } else {
      setErreur("Ce code n'est pas reconnu ou a déjà été activé sur un autre compte. Vérifiez la gravure au dos de votre carte.");
    }
  };

  const simulerNFC = () => {
    setScan(true);
    setErreur("");
    setTimeout(() => valider(CODES_DEMO[0]), 1800);
  };

  return (
    <div style={{
      minHeight: "100vh", background: `radial-gradient(ellipse at 50% 0%, #1A2642 0%, ${C.nuitProfonde} 65%)`,
      display: "flex", flexDirection: "column", alignItems: "center", justifyContent: "center",
      padding: "40px 24px", textAlign: "center",
    }}>
      <div style={{ animation: "apparition 1.2s ease both" }}>
        <Nazar size={96} />
        <h1 style={{
          fontFamily: "'Cormorant Garamond', serif", fontWeight: 500, fontSize: 40,
          color: C.parchemin, margin: "28px 0 4px", letterSpacing: "0.02em",
        }}>
          Pass Mauvais Œil
        </h1>
        <p style={{
          fontFamily: "'Jost', sans-serif", fontWeight: 300, fontSize: 13,
          letterSpacing: "0.28em", textTransform: "uppercase", color: C.nazarClair, margin: 0,
        }}>
          Le grimoire complet des protections
        </p>
      </div>

      <div style={{ maxWidth: 380, width: "100%", marginTop: 44, animation: "apparition 1.2s ease 0.3s both" }}>
        {!mode && (
          <>
            <p style={{ fontFamily: "'EB Garamond', serif", fontSize: 17, color: C.parcheminDoux, lineHeight: 1.6, marginBottom: 24 }}>
              Ce grimoire s'ouvre avec votre carte gravée. Approchez-la de votre téléphone, ou saisissez le code d'activation unique gravé au dos.
            </p>
            <ImageSlot id="IMG-01" sujet="Carte NFC gravée Pass Mauvais Œil" ratio="16/8" src="/images/img-01.jpg" />
            <button onClick={() => setMode("nfc")} style={boutonPrincipal}>Approcher ma carte</button>
            <button onClick={() => setMode("code")} style={boutonSecondaire}>Saisir mon code d'activation</button>
          </>
        )}

        {mode === "nfc" && (
          <div>
            <div style={{
              width: 160, height: 100, margin: "0 auto 24px", borderRadius: 12,
              border: `1.5px solid ${scan ? C.nazarClair : C.ligne}`,
              background: `linear-gradient(135deg, #1B2540, #0F1729)`,
              display: "flex", alignItems: "center", justifyContent: "center",
              boxShadow: scan ? `0 0 30px ${C.nazar}55` : "none",
              transition: "all 0.5s ease", position: "relative", overflow: "hidden",
            }}>
              {scan && <div style={{
                position: "absolute", inset: 0,
                background: `linear-gradient(90deg, transparent, ${C.nazar}33, transparent)`,
                animation: "balayage 1.2s linear infinite",
              }} />}
              <Nazar size={44} glow={false} />
            </div>
            <p style={{ fontFamily: "'EB Garamond', serif", fontSize: 16, color: C.parcheminDoux, marginBottom: 24 }}>
              {scan ? "Lecture de la puce en cours…" : "Placez votre carte contre le dos de votre téléphone."}
            </p>
            {!scan && <button onClick={simulerNFC} style={boutonPrincipal}>Lancer la lecture</button>}
            <button onClick={() => { setMode(null); setScan(false); }} style={boutonTexte}>Retour</button>
          </div>
        )}

        {mode === "code" && (
          <div>
            <input
              value={code}
              onChange={(e) => { setCode(e.target.value); setErreur(""); }}
              placeholder="PMO-XXXX-XXXX"
              style={{
                width: "100%", boxSizing: "border-box", padding: "16px 18px",
                background: "#0D1424", border: `1px solid ${erreur ? "#C96A5C" : C.ligne}`,
                borderRadius: 10, color: C.parchemin, fontSize: 18, letterSpacing: "0.12em",
                fontFamily: "'Jost', sans-serif", textAlign: "center", outline: "none", marginBottom: 14,
              }}
            />
            {erreur && (
              <p style={{ fontFamily: "'Jost', sans-serif", fontSize: 13, color: "#DB9A8E", marginBottom: 14, lineHeight: 1.5 }}>
                {erreur}
              </p>
            )}
            <button onClick={() => valider(code)} style={boutonPrincipal}>Activer ma carte</button>
            <button onClick={() => setMode(null)} style={boutonTexte}>Retour</button>
            <p style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#5E6A85", marginTop: 20, lineHeight: 1.6 }}>
              Démonstration — code d'essai : PMO-2026-0001
            </p>
          </div>
        )}
      </div>

      <p style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#4A5570", marginTop: 48, maxWidth: 340, lineHeight: 1.6 }}>
        Chaque code est unique et se lie définitivement à votre compte lors de l'activation. La carte donne accès à l'intégralité du grimoire.
      </p>
    </div>
  );
}

/* ---------- Accueil ---------- */
function Accueil({ aller }) {
  return (
    <div style={{ padding: "36px 22px 20px", animation: "apparition 0.7s ease both" }}>
      <Nazar size={64} />
      <h2 style={titrePage}>Votre grimoire est ouvert</h2>
      <p style={{ ...texteCourant, textAlign: "center", color: C.parcheminDoux }}>
        L'intégralité du savoir traditionnel de protection, réuni en un seul lieu : repérer, vérifier, se protéger, purifier. Votre carte a tout débloqué.
      </p>
      <ImageSlot id="IMG-A" sujet="Table de grimoire" src="/images/img-a.jpg" />

      {[
        { t: "Le Grimoire", d: `${GRIMOIRE.length} chapitres : signes, rites de vérification, sel, amulettes, talismans, pentacles, autodéfense psychique, traditions du monde…`, page: "grimoire" },
        { t: "Les Rituels", d: `${RITUELS.length} pratiques guidées : Cocon doré, Croix de Lumière, rite de l'huile, méditation du Pharaon…`, page: "rituels" },
        { t: "L'Almanach", d: "Vos protections sur mesure : pierres et parfums de votre signe, jours propices, guide des fumigations.", page: "almanach" },
        { t: "L'Éclairage", d: "Passez en revue les signes que la tradition enseigne à repérer.", page: "eclairage" },
        { t: "Ma Carte", d: "Votre pass gravé et les collections à venir.", page: "carte" },
      ].map((x) => (
        <button key={x.page} onClick={() => aller(x.page)} style={{
          display: "block", width: "100%", textAlign: "left", padding: "18px 20px", marginBottom: 12,
          background: C.nuitCarte, border: `1px solid ${C.ligne}`, borderRadius: 14, cursor: "pointer",
        }}>
          <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 22, fontWeight: 500, color: C.parchemin }}>{x.t}</div>
          <div style={{ fontFamily: "'EB Garamond', serif", fontSize: 14, color: "#93A0B8", marginTop: 3, lineHeight: 1.5 }}>{x.d}</div>
        </button>
      ))}
    </div>
  );
}

/* ---------- Grimoire ---------- */
function Grimoire({ chapitreOuvert, setChapitreOuvert }) {
  const chap = GRIMOIRE.find((c) => c.id === chapitreOuvert);

  if (chap) {
    return (
      <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
        <button onClick={() => setChapitreOuvert(null)} style={{ ...boutonTexte, margin: "0 0 18px", padding: 0, textAlign: "left" }}>
          ← Retour au grimoire
        </button>
        <Eyebrow>{chap.eyebrow}</Eyebrow>
        <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>{chap.titre}</h2>
        {chap.img && <ImageSlot id={chap.img.id} sujet={chap.img.sujet} src={chap.img.src} />}
        {chap.corps.map((p, i) => (
          <p key={i} style={{ ...texteCourant, fontSize: 17, lineHeight: 1.75 }}>
            {i === 0 ? <span style={{
              fontFamily: "'Cormorant Garamond', serif", fontSize: 44, lineHeight: 0.9,
              float: "left", marginRight: 8, marginTop: 6, color: C.or,
            }}>{p.charAt(0)}</span> : null}
            {i === 0 ? p.slice(1) : p}
          </p>
        ))}
        <Divider />
        <p style={{ fontFamily: "'EB Garamond', serif", fontStyle: "italic", fontSize: 15, color: C.nazarClair, lineHeight: 1.6 }}>
          {chap.note}
        </p>
      </div>
    );
  }

  const groupes = {};
  GRIMOIRE.forEach((c) => {
    if (!groupes[c.eyebrow]) groupes[c.eyebrow] = [];
    groupes[c.eyebrow].push(c);
  });

  return (
    <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
      <Eyebrow>Le Grimoire</Eyebrow>
      <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>{GRIMOIRE.length} chapitres</h2>
      <p style={{ ...texteCourant, marginBottom: 24 }}>
        Tout le savoir traditionnel, du repérage des signes aux plus hautes protections. Tout est débloqué.
      </p>
      {Object.entries(groupes).map(([groupe, chapitres]) => (
        <div key={groupe} style={{ marginBottom: 22 }}>
          <Eyebrow color={C.nazarClair}>{groupe}</Eyebrow>
          {chapitres.map((c) => (
            <button key={c.id} onClick={() => setChapitreOuvert(c.id)} style={{
              display: "block", width: "100%", textAlign: "left", padding: "15px 18px", marginBottom: 8,
              background: C.nuitCarte, border: `1px solid ${C.ligne}`, borderRadius: 12, cursor: "pointer",
            }}>
              <span style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 19, fontWeight: 500, color: C.parchemin }}>
                {c.titre}
              </span>
              <div style={{ fontFamily: "'EB Garamond', serif", fontSize: 13.5, color: "#8B98B0", marginTop: 3 }}>{c.resume}</div>
            </button>
          ))}
        </div>
      ))}
    </div>
  );
}

/* ---------- Rituels ---------- */
function Rituels() {
  const [ouvert, setOuvert] = useState(null);
  const [etape, setEtape] = useState(0);
  const rit = RITUELS.find((r) => r.id === ouvert);

  if (rit) {
    const fini = etape >= rit.etapes.length;
    return (
      <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
        <button onClick={() => { setOuvert(null); setEtape(0); }} style={{ ...boutonTexte, margin: "0 0 18px", padding: 0, textAlign: "left" }}>
          ← Tous les rituels
        </button>
        <Eyebrow color={C.nazarClair}>Pratique guidée · {rit.duree}</Eyebrow>
        <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>{rit.titre}</h2>

        {!fini ? (
          <div style={{ padding: "28px 24px", borderRadius: 16, background: C.nuitCarte, border: `1px solid ${C.ligne}`, textAlign: "center", minHeight: 190, display: "flex", flexDirection: "column", justifyContent: "center" }}>
            <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 12, letterSpacing: "0.2em", color: C.or, marginBottom: 14 }}>
              ÉTAPE {etape + 1} / {rit.etapes.length}
            </div>
            <p style={{ fontFamily: "'EB Garamond', serif", fontSize: 18, lineHeight: 1.7, color: C.parchemin, margin: 0 }}>
              {rit.etapes[etape]}
            </p>
          </div>
        ) : (
          <div style={{ padding: "34px 24px", borderRadius: 16, background: C.nuitCarte, border: `1px solid ${C.or}44`, textAlign: "center" }}>
            <Nazar size={52} />
            <p style={{ ...texteCourant, marginTop: 18, textAlign: "center" }}>
              Le rite est accompli. La tradition dit que la protection est en place — et que la sérénité qui vous gagne en est le premier signe.
            </p>
          </div>
        )}

        <div style={{ display: "flex", gap: 10, marginTop: 18 }}>
          {etape > 0 && !fini && (
            <button onClick={() => setEtape(etape - 1)} style={{ ...boutonSecondaire, marginBottom: 0, flex: 1 }}>Précédent</button>
          )}
          {!fini ? (
            <button onClick={() => setEtape(etape + 1)} style={{ ...boutonPrincipal, marginBottom: 0, flex: 2 }}>
              {etape === rit.etapes.length - 1 ? "Terminer" : "Étape suivante"}
            </button>
          ) : (
            <button onClick={() => { setOuvert(null); setEtape(0); }} style={{ ...boutonPrincipal, marginBottom: 0, flex: 1 }}>
              Revenir aux rituels
            </button>
          )}
        </div>
      </div>
    );
  }

  return (
    <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
      <Eyebrow color={C.nazarClair}>Les Rituels</Eyebrow>
      <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>{RITUELS.length} pratiques guidées</h2>
      <p style={{ ...texteCourant, marginBottom: 20 }}>
        Vérifier, protéger, purifier : chaque rite du répertoire traditionnel, pas à pas, tel que les anciens le transmettaient.
      </p>
      <ImageSlot id="IMG-B" sujet="Allumer l'encens" ratio="16/7" src="/images/img-b.jpg" />
      {RITUELS.map((r) => (
        <button key={r.id} onClick={() => setOuvert(r.id)} style={{
          display: "block", width: "100%", textAlign: "left", padding: "16px 18px", marginBottom: 10,
          background: C.nuitCarte, border: `1px solid ${C.ligne}`, borderRadius: 12, cursor: "pointer",
        }}>
          <div style={{ display: "flex", justifyContent: "space-between", alignItems: "baseline" }}>
            <span style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 19, fontWeight: 500, color: C.parchemin }}>{r.titre}</span>
            <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: C.nazarClair, letterSpacing: "0.1em", whiteSpace: "nowrap", marginLeft: 10 }}>{r.duree}</span>
          </div>
          <div style={{ fontFamily: "'EB Garamond', serif", fontSize: 13.5, color: "#8B98B0", marginTop: 4, lineHeight: 1.5 }}>{r.intro}</div>
        </button>
      ))}
    </div>
  );
}

/* ---------- Éclairage ---------- */
function Eclairage({ aller, setChapitreOuvert }) {
  const [coches, setCoches] = useState([]);
  const [resultat, setResultat] = useState(false);

  const basculer = (i) => {
    setCoches(coches.includes(i) ? coches.filter((x) => x !== i) : [...coches, i]);
  };

  const score = coches.reduce((acc, i) => acc + SIGNES[i].poids, 0);

  const lecture = () => {
    if (score === 0) return {
      titre: "Le ciel est clair",
      texte: "Aucun des signes du répertoire traditionnel n'est présent. Les anciens diraient que votre aura vitale est solide. C'est le moment idéal pour l'entretenir : le Cocon doré pratiqué régulièrement, une coupelle de sel dans la maison, et le tour est joué.",
      rituels: ["cocon"],
      chapitres: ["protections-populaires"],
    };
    if (score <= 3) return {
      titre: "Quelques nuages passagers",
      texte: "La tradition lirait ici des influences légères — le lot commun des pensées négatives qui circulent entre les êtres, souvent au sein même de l'entourage proche. Rien que le répertoire de base ne dissipe : un bouclier de pensée, quelques gestes protecteurs, et l'atmosphère s'éclaircit.",
      rituels: ["cocon", "cocon-rapide"],
      chapitres: ["signes", "protections-populaires"],
    };
    if (score <= 7) return {
      titre: "La tradition inviterait à vérifier",
      texte: "Plusieurs signes du répertoire sont réunis. Devant pareil faisceau, les anciens ne concluaient jamais d'emblée : ils soumettaient le soupçon à l'épreuve — le rite de l'huile pour la personne, le rite du sel pour la maison. Puis, quel que soit le verdict, ils purifiaient : l'encens dissipe ce qu'il révèle. Souvenez-vous du chiffre des maîtres : neuf cas sur dix ne sont que pensées négatives ordinaires, que ces pratiques suffisent à disperser.",
      rituels: ["huile", "sel-rite", "encens"],
      chapitres: ["rites-verification", "signes"],
    };
    return {
      titre: "Le grand protocole des anciens",
      texte: "Le faisceau de signes est dense — c'est précisément pour ces situations que la tradition a forgé son protocole complet : vérifier par le rite de l'huile et celui du sel ; purifier la maison à l'encens puis par la neuvaine des neuf bougies ; dresser le Cocon doré chaque jour ; et si un objet étrange a réellement été découvert, suivre à la lettre le chapitre sur la neutralisation — sans jamais le brûler. Un dernier mot, hérité des maîtres eux-mêmes : fuyez quiconque vous affirmerait contre monnaie que vous êtes ensorcelé. La tradition vous a tout transmis ici — et si le poids devient lourd à porter, en parler à un proche de confiance fait aussi partie, depuis toujours, des remèdes des anciens.",
      rituels: ["huile", "encens", "bougies", "cocon"],
      chapitres: ["rites-verification", "neutralisation", "retour"],
    };
  };

  if (resultat) {
    const l = lecture();
    return (
      <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
        <div style={{ textAlign: "center" }}><Nazar size={52} /></div>
        <Eyebrow>Lecture selon la tradition</Eyebrow>
        <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>{l.titre}</h2>
        <p style={{ ...texteCourant, fontSize: 17 }}>{l.texte}</p>
        <Divider />
        <Eyebrow color={C.nazarClair}>Rites conseillés</Eyebrow>
        {l.rituels.map((id) => {
          const r = RITUELS.find((x) => x.id === id);
          return (
            <div key={id} style={{ padding: "13px 16px", borderRadius: 12, background: C.nuitCarte, border: `1px solid ${C.ligne}`, marginBottom: 8 }}>
              <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 19, color: C.parchemin }}>{r.titre}</div>
              <button onClick={() => aller("rituels")} style={{ ...boutonTexte, textAlign: "left", padding: "4px 0 0", margin: 0, color: C.or }}>
                Ouvrir dans les Rituels →
              </button>
            </div>
          );
        })}
        <div style={{ height: 10 }} />
        <Eyebrow>Chapitres à consulter</Eyebrow>
        {l.chapitres.map((id) => {
          const c = GRIMOIRE.find((x) => x.id === id);
          return (
            <div key={id} style={{ padding: "13px 16px", borderRadius: 12, background: C.nuitCarte, border: `1px solid ${C.ligne}`, marginBottom: 8 }}>
              <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 19, color: C.parchemin }}>{c.titre}</div>
              <button onClick={() => { setChapitreOuvert(id); aller("grimoire"); }} style={{ ...boutonTexte, textAlign: "left", padding: "4px 0 0", margin: 0, color: C.or }}>
                Ouvrir dans le Grimoire →
              </button>
            </div>
          );
        })}
        <button onClick={() => { setResultat(false); setCoches([]); }} style={{ ...boutonTexte, marginTop: 14 }}>
          Recommencer la lecture
        </button>
      </div>
    );
  }

  return (
    <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
      <Eyebrow>L'Éclairage</Eyebrow>
      <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>Les signes selon la tradition</h2>
      <p style={{ ...texteCourant }}>
        Voici les signes que le répertoire traditionnel enseigne à repérer. Cochez ceux qui résonnent avec votre situation : la lecture vous orientera vers les rites de vérification et les protections que les anciens prescrivaient.
      </p>
      {SIGNES.map((s, i) => (
        <button key={i} onClick={() => basculer(i)} style={{
          display: "flex", alignItems: "center", gap: 12, width: "100%", textAlign: "left",
          padding: "13px 16px", marginBottom: 8, borderRadius: 12, cursor: "pointer",
          background: coches.includes(i) ? "rgba(79,163,181,0.12)" : C.nuitCarte,
          border: `1px solid ${coches.includes(i) ? C.nazar : C.ligne}`,
        }}>
          <div style={{
            width: 20, height: 20, borderRadius: 6, flexShrink: 0,
            border: `1.5px solid ${coches.includes(i) ? C.nazarClair : "#5E6A85"}`,
            background: coches.includes(i) ? C.nazar : "transparent",
            display: "flex", alignItems: "center", justifyContent: "center",
            color: "#0B111F", fontSize: 13, fontWeight: 700,
          }}>
            {coches.includes(i) ? "✓" : ""}
          </div>
          <span style={{ fontFamily: "'EB Garamond', serif", fontSize: 15.5, color: C.parchemin, lineHeight: 1.45 }}>{s.s}</span>
        </button>
      ))}
      <button onClick={() => setResultat(true)} style={{ ...boutonPrincipal, marginTop: 14 }}>
        Lire selon la tradition
      </button>
    </div>
  );
}

/* ---------- Ma Carte ---------- */
function MaCarte({ code }) {
  return (
    <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
      <Eyebrow>Ma Carte</Eyebrow>
      <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>Votre pass gravé</h2>

      <div style={{
        borderRadius: 18, padding: "26px 22px", marginBottom: 18,
        background: `linear-gradient(140deg, #1E2A4A 0%, #10182B 70%)`,
        border: `1px solid ${C.or}66`, position: "relative", overflow: "hidden",
      }}>
        <div style={{ position: "absolute", top: -30, right: -30, opacity: 0.15 }}>
          <Nazar size={140} glow={false} />
        </div>
        <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, letterSpacing: "0.24em", textTransform: "uppercase", color: C.or }}>
          Édition complète
        </div>
        <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 30, color: C.parchemin, margin: "8px 0 20px" }}>
          Pass Mauvais Œil
        </div>
        <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 13, letterSpacing: "0.14em", color: C.parcheminDoux }}>
          {code}
        </div>
        <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#6B7690", marginTop: 6 }}>
          Liée définitivement à votre compte · Puce NFC authentifiée · Accès intégral
        </div>
      </div>

      <ImageSlot id="IMG-C" sujet="La carte physique" ratio="16/8" src="/images/img-c.jpg" />

      <h3 style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 22, fontWeight: 500, color: C.parchemin, marginBottom: 8 }}>
        Ce que votre carte a débloqué
      </h3>
      <p style={{ ...texteCourant }}>
        L'intégralité du grimoire — {GRIMOIRE.length} chapitres — et les {RITUELS.length} rites guidés, sans aucune restriction. Votre carte est la clé unique de ce savoir : gravée, authentifiée, impossible à dupliquer ou à partager.
      </p>

      <h3 style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 22, fontWeight: 500, color: C.parchemin, marginBottom: 8 }}>
        À venir
      </h3>
      <p style={{ ...texteCourant }}>
        De nouveaux contenus enrichiront régulièrement votre grimoire — nouveaux rituels, prières traditionnelles, chapitres saisonniers comme la nuit de la Saint-Jean — et se débloqueront automatiquement sur votre compte, sans surcoût : c'est le privilège des détenteurs de la carte gravée. Des cartes d'éditions limitées pourront ouvrir, plus tard, des collections thématiques nouvelles.
      </p>

      <Divider />
      <p style={{ fontFamily: "'Jost', sans-serif", fontSize: 10.5, color: "#4A5570", lineHeight: 1.7 }}>
        Le Pass Mauvais Œil transmet un patrimoine : traditions populaires, folklore et spiritualité, présentés tels que les textes anciens les rapportent. Ses contenus ne remplacent pas l'avis d'un professionnel de santé.
      </p>
    </div>
  );
}

/* ---------- Atelier du talisman ---------- */
function AtelierTalisman() {
  const [intention, setIntention] = useState(null);
  const [lever, setLever] = useState("06:30");
  const [coucher, setCoucher] = useState("21:30");
  const [dateChoisie, setDateChoisie] = useState(() => new Date().toISOString().slice(0, 10));
  const choix = INTENTIONS.find((i) => i.but === intention);
  const p = choix ? PLANETES[choix.planete] : null;
  const calc = choix ? calculerHeures(lever, coucher, dateChoisie) : null;
  const heuresPlanete = calc ? calc.heures.filter((h) => h.planete === choix.planete) : [];
  const jourIdeal = p && calc ? p.jour.toLowerCase() === calc.nomJour : false;
  const estAujourdhui = dateChoisie === new Date().toISOString().slice(0, 10);
  const dateLisible = calc ? `${calc.nomJour} ${dateChoisie.split("-").reverse().join("/")}` : "";

  if (!choix) {
    return (
      <div style={{ animation: "apparition 0.4s ease both" }}>
        <p style={{ ...texteCourant, fontSize: 15 }}>
          Fabriquer son talisman en respectant les correspondances — planète, jour, heure magique, métal, couleur — est le sommet de l'art traditionnel. Tout commence par l'intention : elle détermine la planète, et la planète détermine tout le reste.
        </p>
        {INTENTIONS.map((i) => (
          <button key={i.but} onClick={() => setIntention(i.but)} style={{
            display: "block", width: "100%", textAlign: "left", padding: "14px 16px", marginBottom: 8,
            background: C.nuitCarte, border: `1px solid ${C.ligne}`, borderRadius: 12, cursor: "pointer",
          }}>
            <div style={{ display: "flex", justifyContent: "space-between", alignItems: "baseline" }}>
              <span style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 18, color: C.parchemin }}>{i.but}</span>
              <span style={{ fontSize: 16, color: PLANETES[i.planete].teinte }}>{PLANETES[i.planete].symbole}</span>
            </div>
            <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#8B98B0", marginTop: 3, letterSpacing: "0.06em" }}>
              Planète : {i.planete} · Jour : {PLANETES[i.planete].jour}
            </div>
          </button>
        ))}
      </div>
    );
  }

  return (
    <div style={{ animation: "apparition 0.4s ease both" }}>
      <button onClick={() => setIntention(null)} style={{ ...boutonTexte, margin: "0 0 14px", padding: 0, textAlign: "left" }}>
        ← Changer d'intention
      </button>

      <div style={{
        borderRadius: 16, padding: "20px", marginBottom: 14,
        background: `linear-gradient(140deg, #1E2A4A 0%, #131C33 70%)`, border: `1px solid ${p.teinte}66`,
      }}>
        <div style={{ display: "flex", alignItems: "center", gap: 12, marginBottom: 10 }}>
          <span style={{ fontSize: 34, color: p.teinte, lineHeight: 1 }}>{p.symbole}</span>
          <div>
            <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 24, color: C.parchemin }}>{choix.planete}</div>
            <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#8B98B0", letterSpacing: "0.08em" }}>{choix.but}</div>
          </div>
        </div>
        <p style={{ fontFamily: "'EB Garamond', serif", fontSize: 14.5, color: C.parcheminDoux, lineHeight: 1.55, margin: "0 0 12px" }}>{choix.detail}</p>
        {[
          ["Jour de fabrication", p.jour],
          ["Métal", p.metal],
          ["Couleur", p.couleur],
          ["Fumigation", p.encens],
          ["Plantes & parfums", p.plantes],
          ["Support traditionnel", p.support],
          ["Esprit planétaire", p.esprit],
          ["Intelligence planétaire", p.intelligence],
        ].map(([l, v]) => (
          <div key={l} style={{ display: "flex", justifyContent: "space-between", gap: 12, padding: "7px 0", borderBottom: "1px solid rgba(201,164,92,0.12)" }}>
            <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, letterSpacing: "0.1em", textTransform: "uppercase", color: C.nazarClair, whiteSpace: "nowrap" }}>{l}</span>
            <span style={{ fontFamily: "'EB Garamond', serif", fontSize: 14.5, color: C.parchemin, textAlign: "right" }}>{v}</span>
          </div>
        ))}
      </div>

      <Eyebrow>Le talisman traditionnel de {choix.planete}</Eyebrow>
      <p style={{ ...texteCourant, fontSize: 14.5 }}>
        Voici le modèle ancien, tel que la tradition hermétique le transmet : au recto, le sceau planétaire avec le symbole de la planète ; au verso, les noms de l'Esprit et de l'Intelligence — {p.esprit} et {p.intelligence} — inscrits en caractères hébraïques, chaque lettre portant sa valeur numérique. C'est ce modèle que vous reproduirez fidèlement, ou que l'atelier moderne ci-dessous adapte.
      </p>
      <div style={{ display: "flex", gap: 10, marginBottom: 18 }}>
        <div style={{ flex: 1 }}>
          <ImageSlot id={`IMG-${p.img}-R`} sujet={`RECTO — Sceau planétaire de ${choix.planete}`} ratio="1/1" src={`/images/img-${p.img.toLowerCase()}-r.png`} />
        </div>
        <div style={{ flex: 1 }}>
          <ImageSlot id={`IMG-${p.img}-V`} sujet={`VERSO — Noms hébraïques de ${p.esprit} et ${p.intelligence}`} ratio="1/1" src={`/images/img-${p.img.toLowerCase()}-v.png`} />
        </div>
      </div>

      <Eyebrow color={C.nazarClair}>L'heure magique — {estAujourdhui ? `aujourd'hui (${calc.nomJour})` : dateLisible}</Eyebrow>
      <p style={{ ...texteCourant, fontSize: 14.5 }}>
        La journée traditionnelle compte 12 heures inégales de jour (du lever au coucher du soleil) et 12 de nuit, gouvernées tour à tour par les planètes selon l'ordre chaldéen. La première heure du jour appartient au maître du jour — le {calc.nomJour}, c'est {calc.maitre}. Choisissez la date de fabrication (idéalement un {p.jour.toLowerCase()}) et indiquez les heures de soleil de votre ville :
      </p>
      <label style={{ display: "block", marginBottom: 10 }}>
        <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 10.5, letterSpacing: "0.08em", textTransform: "uppercase", color: "#8B98B0", display: "block", marginBottom: 4 }}>Date de fabrication</span>
        <input type="date" value={dateChoisie} onChange={(e) => setDateChoisie(e.target.value)} style={{
          width: "100%", boxSizing: "border-box", padding: "10px 12px", background: "#0D1424",
          border: `1px solid ${jourIdeal ? C.or : C.ligne}`, borderRadius: 9, color: C.parchemin,
          fontFamily: "'Jost', sans-serif", fontSize: 15, outline: "none",
        }} />
      </label>
      <div style={{ display: "flex", gap: 10, marginBottom: 12 }}>
        {[["Lever du soleil", lever, setLever], ["Coucher du soleil", coucher, setCoucher]].map(([l, v, set]) => (
          <label key={l} style={{ flex: 1 }}>
            <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 10.5, letterSpacing: "0.08em", textTransform: "uppercase", color: "#8B98B0", display: "block", marginBottom: 4 }}>{l}</span>
            <input type="time" value={v} onChange={(e) => set(e.target.value)} style={{
              width: "100%", boxSizing: "border-box", padding: "10px 12px", background: "#0D1424",
              border: `1px solid ${C.ligne}`, borderRadius: 9, color: C.parchemin,
              fontFamily: "'Jost', sans-serif", fontSize: 15, outline: "none",
            }} />
          </label>
        ))}
      </div>

      {jourIdeal && (
        <div style={{ padding: "11px 14px", borderRadius: 10, background: "rgba(201,164,92,0.12)", border: `1px solid ${C.or}55`, marginBottom: 10 }}>
          <span style={{ fontFamily: "'EB Garamond', serif", fontSize: 14.5, color: C.orClair }}>
            ✦ Jour parfait ! Le {dateLisible.split(" ")[0]} {estAujourdhui ? "(aujourd'hui)" : dateChoisie.split("-").reverse().join("/")} est le jour même de {choix.planete}. Jour et heure accordés : la configuration la plus puissante de la tradition.
          </span>
        </div>
      )}

      {!jourIdeal && (
        <div style={{ padding: "10px 14px", borderRadius: 10, background: "rgba(79,163,181,0.08)", border: `1px solid ${C.ligne}`, marginBottom: 10 }}>
          <span style={{ fontFamily: "'EB Garamond', serif", fontSize: 14, color: "#A8B2C6" }}>
            Le {calc.nomJour} appartient à {calc.maitre}. Pour la configuration parfaite, choisissez le prochain {p.jour.toLowerCase()} — jour de {choix.planete} — dans le sélecteur ci-dessus. Les heures de {choix.planete} du jour choisi restent néanmoins propices :
          </span>
        </div>
      )}
      <div style={{ borderRadius: 12, overflow: "hidden", border: `1px solid ${C.ligne}`, marginBottom: 10 }}>
        {heuresPlanete.map((h, i) => (
          <div key={i} style={{
            display: "flex", justifyContent: "space-between", padding: "11px 16px",
            background: i % 2 ? "#161F38" : C.nuitCarte,
          }}>
            <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 12, letterSpacing: "0.08em", color: C.nazarClair }}>
              {h.type === "jour" ? "☀ Heure de jour" : "☾ Heure de nuit"} n°{h.n}
            </span>
            <span style={{ fontFamily: "'EB Garamond', serif", fontSize: 15.5, color: C.parchemin }}>
              {h.debut} → {h.fin}
            </span>
          </div>
        ))}
      </div>
      <p style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#5E6A85", lineHeight: 1.6, marginBottom: 18 }}>
        Voici les fenêtres où {choix.planete} gouverne l'heure le jour choisi, calculées pour vos horaires de soleil (pensez à les ajuster selon la saison de la date). {p.jour} reste le jour idéal ; pour un calcul astronomique précis selon votre ville, la référence est tempus-magis.fr. La tradition ajoute : lune croissante pour attirer, décroissante pour bannir.
      </p>

      <Eyebrow>La confection, pas à pas</Eyebrow>
      {[
        `Préparez le support : ${p.support.toLowerCase()} — ou, à défaut, un beau papier aux teintes de la planète (${p.couleur.toLowerCase()}). Originellement gravé dans le métal ou la pierre, le talisman a fait du parchemin son support favori en Occident.`,
        `Le ${p.jour.toLowerCase()}, à l'une des heures de ${choix.planete} ci-dessus, installez-vous au calme. Brûlez la fumigation de la planète (${p.encens.toLowerCase()}), allumée avec une allumette en bois.`,
        `Accomplissez la Croix de Lumière pour concentrer l'énergie (rituel guidé dans l'onglet Rituels).`,
        `Tracez au recto le symbole de la planète ${p.symbole} — d'un seul geste, avec une concentration totale : la qualité de la concentration fait tout, disent les textes. Vous pouvez l'entourer du sceau planétaire ou de votre signe zodiacal (talisman astrologique), ou y joindre les noms de l'Esprit et de l'Intelligence de la planète — ${p.esprit} et ${p.intelligence} — selon la tradition hermétique (talisman mixte).`,
        `Au verso, inscrivez votre intention en une phrase brève et affirmative, ou votre nom sous forme de symbole personnel — souvenez-vous du nom secret des pharaons.`,
        `Consacrez ensuite le talisman par le rituel des quatre éléments (rituel « Consacrer un talisman », dans l'onglet Rituels), avec ses formules traditionnelles.`,
        `Portez-le sur vous, glissez-le dans un sac médecine de soie ou de cuir, ou placez-le dans le lieu qu'il doit garder. Rechargez-le une à deux fois l'an, ou à chaque retour du jour de sa planète qui vous semblera propice.`,
      ].map((t, i) => (
        <div key={i} style={{ display: "flex", gap: 12, marginBottom: 10 }}>
          <div style={{
            width: 26, height: 26, borderRadius: "50%", flexShrink: 0, marginTop: 2,
            border: `1px solid ${C.or}`, display: "flex", alignItems: "center", justifyContent: "center",
            fontFamily: "'Jost', sans-serif", fontSize: 12, color: C.orClair,
          }}>{i + 1}</div>
          <p style={{ fontFamily: "'EB Garamond', serif", fontSize: 15, lineHeight: 1.6, color: C.parcheminDoux, margin: 0 }}>{t}</p>
        </div>
      ))}
    </div>
  );
}

/* ---------- Almanach ---------- */
function Almanach() {
  const [signe, setSigne] = useState(null);
  const [section, setSection] = useState("profil"); // profil | pierres | fumigations | calendrier
  const z = ZODIAQUE.find((x) => x.signe === signe);

  const Onglet = ({ id, label }) => (
    <button onClick={() => setSection(id)} style={{
      flex: 1, padding: "9px 4px", background: section === id ? "rgba(201,164,92,0.14)" : "transparent",
      border: `1px solid ${section === id ? C.or : C.ligne}`, borderRadius: 9, cursor: "pointer",
      fontFamily: "'Jost', sans-serif", fontSize: 10.5, letterSpacing: "0.06em",
      color: section === id ? C.orClair : "#8B98B0", textTransform: "uppercase",
    }}>{label}</button>
  );

  const Ligne = ({ label, valeur }) => (
    <div style={{ display: "flex", justifyContent: "space-between", gap: 14, padding: "9px 0", borderBottom: `1px solid rgba(201,164,92,0.12)` }}>
      <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 11.5, letterSpacing: "0.1em", textTransform: "uppercase", color: C.nazarClair, whiteSpace: "nowrap" }}>{label}</span>
      <span style={{ fontFamily: "'EB Garamond', serif", fontSize: 15.5, color: C.parchemin, textAlign: "right" }}>{valeur}</span>
    </div>
  );

  return (
    <div style={{ padding: "30px 22px 20px", animation: "apparition 0.5s ease both" }}>
      <Eyebrow>L'Almanach</Eyebrow>
      <h2 style={{ ...titrePage, textAlign: "left", marginTop: 0 }}>Vos protections sur mesure</h2>
      <p style={{ ...texteCourant, marginBottom: 16 }}>
        Toutes les correspondances de la tradition — et l'Atelier pour confectionner votre talisman selon les règles de l'art : planète, jour, heure magique, métal, couleur.
      </p>

      <div style={{ display: "flex", gap: 6, marginBottom: 20 }}>
        <Onglet id="profil" label="Signe" />
        <Onglet id="talisman" label="Talisman" />
        <Onglet id="pierres" label="Pierres" />
        <Onglet id="fumigations" label="Fumées" />
        <Onglet id="calendrier" label="Jours" />
      </div>

      {section === "profil" && (
        <div>
          {!z ? (
            <>
              <p style={{ ...texteCourant }}>
                Choisissez votre signe : la tradition des talismans astrologiques lui associe des nombres, un métal, une couleur, un animal, une fleur, des parfums magiques et des pierres qui vous sont propres.
              </p>
              <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr 1fr", gap: 8 }}>
                {ZODIAQUE.map((x) => (
                  <button key={x.signe} onClick={() => setSigne(x.signe)} style={{
                    padding: "13px 6px", background: C.nuitCarte, border: `1px solid ${C.ligne}`,
                    borderRadius: 11, cursor: "pointer", textAlign: "center",
                  }}>
                    <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 17, color: C.parchemin }}>{x.signe}</div>
                    <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 9, color: "#6B7690", marginTop: 3 }}>{x.dates}</div>
                  </button>
                ))}
              </div>
            </>
          ) : (
            <div style={{ animation: "apparition 0.4s ease both" }}>
              <div style={{
                borderRadius: 16, padding: "22px 20px", background: `linear-gradient(140deg, #1E2A4A 0%, #131C33 70%)`,
                border: `1px solid ${C.or}55`,
              }}>
                <div style={{ display: "flex", justifyContent: "space-between", alignItems: "baseline", marginBottom: 6 }}>
                  <span style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 28, color: C.parchemin }}>{z.signe}</span>
                  <span style={{ fontFamily: "'Jost', sans-serif", fontSize: 11, color: "#8B98B0" }}>{z.dates}</span>
                </div>
                <Ligne label="Nombres" valeur={z.nombres} />
                <Ligne label="Métal" valeur={z.metal} />
                <Ligne label="Couleur" valeur={z.couleur} />
                <Ligne label="Animal" valeur={z.animal} />
                <Ligne label="Fleur" valeur={z.fleur} />
                <Ligne label="Parfums magiques" valeur={z.parfums} />
                <Ligne label="Pierres" valeur={z.pierres.join(" · ")} />
              </div>
              <p style={{ ...texteCourant, fontSize: 14.5, marginTop: 14, color: "#A8B2C6" }}>
                Comment s'en servir : choisissez votre amulette parmi vos pierres (détails dans l'onglet Pierres), brûlez vos parfums magiques pour vos purifications personnelles, privilégiez votre couleur dans les vêtements ou objets protecteurs, et gravez ou choisissez vos talismans dans votre métal. Chargez le tout avec le rituel « Charger une amulette ».
              </p>
              <button onClick={() => setSigne(null)} style={{ ...boutonSecondaire }}>Changer de signe</button>
            </div>
          )}
        </div>
      )}

      {section === "talisman" && <AtelierTalisman />}

      {section === "pierres" && (
        <div style={{ animation: "apparition 0.4s ease both" }}>
          <p style={{ ...texteCourant, fontSize: 15 }}>
            Les pierres ont accumulé leurs énergies pendant des millions d'années — « un souffle de l'éternité », disent les textes. Chacune a sa vertu propre. Nettoyez-les souvent à l'eau courante, chargez-les avec le rituel dédié.
          </p>
          {PIERRES.map((p) => (
            <div key={p.nom} style={{ padding: "13px 16px", marginBottom: 8, borderRadius: 12, background: C.nuitCarte, border: `1px solid ${C.ligne}` }}>
              <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 19, color: C.orClair }}>{p.nom}</div>
              <div style={{ fontFamily: "'EB Garamond', serif", fontSize: 14.5, color: C.parcheminDoux, marginTop: 3, lineHeight: 1.55 }}>{p.vertu}</div>
            </div>
          ))}
        </div>
      )}

      {section === "fumigations" && (
        <div style={{ animation: "apparition 0.4s ease both" }}>
          <ImageSlot id="IMG-27" sujet="Encens et myrrhe" ratio="16/7" src="/images/img-27.jpg" />
          {FUMIGATIONS.map((f) => (
            <div key={f.nom} style={{ padding: "13px 16px", marginBottom: 8, borderRadius: 12, background: C.nuitCarte, border: `1px solid ${C.ligne}` }}>
              <div style={{ fontFamily: "'Cormorant Garamond', serif", fontSize: 19, color: C.orClair }}>{f.nom}</div>
              <div style={{ fontFamily: "'EB Garamond', serif", fontSize: 14.5, color: C.parcheminDoux, marginTop: 3, lineHeight: 1.55 }}>{f.usage}</div>
            </div>
          ))}
        </div>
      )}

      {section === "calendrier" && (
        <div style={{ animation: "apparition 0.4s ease both" }}>
          <p style={{ ...texteCourant, fontSize: 15 }}>
            La tradition a ses heures : agir au bon moment, c'est déjà la moitié du rite.
          </p>
          {CALENDRIER.map((c) => (
            <div key={c.quand} style={{ padding: "13px 16px", marginBottom: 8, borderRadius: 12, background: C.nuitCarte, border: `1px solid ${C.ligne}` }}>
              <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 11.5, letterSpacing: "0.1em", textTransform: "uppercase", color: C.nazarClair }}>{c.quand}</div>
              <div style={{ fontFamily: "'EB Garamond', serif", fontSize: 14.5, color: C.parcheminDoux, marginTop: 4, lineHeight: 1.55 }}>{c.quoi}</div>
            </div>
          ))}
        </div>
      )}
    </div>
  );
}

/* ---------- Navigation & App ---------- */
const ONGLETS = [
  { id: "accueil", label: "Accueil", ic: "◉" },
  { id: "grimoire", label: "Grimoire", ic: "❦" },
  { id: "rituels", label: "Rituels", ic: "✦" },
  { id: "almanach", label: "Almanach", ic: "☼" },
  { id: "eclairage", label: "Éclairage", ic: "☾" },
  { id: "carte", label: "Ma Carte", ic: "▣" },
];

export default function PassMauvaisOeil() {
  const [session, setSession] = useState(null);
  const [page, setPage] = useState("accueil");
  const [chapitreOuvert, setChapitreOuvert] = useState(null);
  const contenu = useRef(null);

  useEffect(() => { if (contenu.current) contenu.current.scrollTop = 0; }, [page, chapitreOuvert]);

  return (
    <div style={{ background: C.nuit, minHeight: "100vh" }}>
      <style>{FONTS + `
        * { -webkit-tap-highlight-color: transparent; }
        button { transition: opacity 0.2s ease, border-color 0.2s ease; }
        button:active { opacity: 0.75; }
        @keyframes respire { 0%,100% { transform: scale(1); opacity: 0.7; } 50% { transform: scale(1.12); opacity: 1; } }
        @keyframes apparition { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes balayage { from { transform: translateX(-100%); } to { transform: translateX(100%); } }
        @media (prefers-reduced-motion: reduce) { * { animation: none !important; } }
      `}</style>

      {!session ? (
        <Activation onActive={setSession} />
      ) : (
        <div style={{ maxWidth: 520, margin: "0 auto", display: "flex", flexDirection: "column", height: "100vh" }}>
          <div ref={contenu} style={{ flex: 1, overflowY: "auto", paddingBottom: 20 }}>
            {page === "accueil" && <Accueil aller={setPage} />}
            {page === "grimoire" && <Grimoire chapitreOuvert={chapitreOuvert} setChapitreOuvert={setChapitreOuvert} />}
            {page === "rituels" && <Rituels />}
            {page === "almanach" && <Almanach />}
            {page === "eclairage" && <Eclairage aller={setPage} setChapitreOuvert={setChapitreOuvert} />}
            {page === "carte" && <MaCarte code={session.code} />}
          </div>
          <nav style={{
            display: "flex", borderTop: `1px solid ${C.ligne}`, background: C.nuitProfonde,
            paddingBottom: "env(safe-area-inset-bottom)",
          }}>
            {ONGLETS.map((o) => (
              <button key={o.id} onClick={() => { setPage(o.id); if (o.id !== "grimoire") setChapitreOuvert(null); }} style={{
                flex: 1, padding: "12px 4px 10px", background: "none", border: "none", cursor: "pointer",
                color: page === o.id ? C.or : "#5E6A85",
              }}>
                <div style={{ fontSize: 17, lineHeight: 1 }}>{o.ic}</div>
                <div style={{ fontFamily: "'Jost', sans-serif", fontSize: 10, letterSpacing: "0.08em", marginTop: 4 }}>{o.label}</div>
              </button>
            ))}
          </nav>
        </div>
      )}
    </div>
  );
}
