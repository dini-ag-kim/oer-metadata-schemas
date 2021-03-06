---
title: "Visitenkarte für OER-Services"
date: 2019-03-09
author: Adrian Pohl, Annett Zobel, Matthias Hupfer, Steffen Hippeli, Torsten Simon
et al.
---

```json
{
   "@context":"http://schema.org/",
   "id":"https://playground.oer-contentbuffet.info/edu-sharing/",
   "type":[
      "Service",
      "WebSite"
   ],
   "name":"Jointly OER Playground",
   "image":"https://playground.oer-contentbuffet.info/edu-sharing/assets/images/sources/home.png",
   "logo":"https://playground.oer-contentbuffet.info/edu-sharing/assets/images/edu-white-alpha.svg",
   "inLanguage":[
      "de",
      "en"
   ],
   "description":"Das Verbundprojekt JOINTLY unterstützt OER-Akteure bei der Entwicklung und Verbreitung ihrer offenen Bildungsmaterialien. Es vermittelt die Beratung durch ExpertInnen zu Recht, Produktion, Didaktik und IT und organisiert Kooperationsaktivitäten zwischen OER-Akteuren. JOINTLY entwickelt gemeinschaftlich OER-förderliche Softwarewerkzeuge sowie Arbeits- und Vertriebsinstrumente.",
   "serviceType":"Repository",
   "audience":[
     "http://purl.org/dcx/lrmi-vocabs/educationalAudienceRole/teacher",
     "http://purl.org/dcx/lrmi-vocabs/educationalAudienceRole/peerTutor"
   ],
   "about": ["https://w3id.org/class/esc/n0541"],
   "isAccessibleForFree":true,
   "provider":[
      {
         "type":"Organization",
         "name":"JOINTLY – Qualifizierung und kooperative Unterstützung für OER – ein Buffet der Kooperation",
         "email":"info@jointly.info",
         "location":{
            "type":"Place",
            "geo":{
               "type": "GeoCoordinates",
               "longitude":11.3271834,
               "latitude":50.9736279
            },
            "address":{
               "type":"PostalAddress",
               "addressCountry":"DE",
               "streetAddress":"Bauhausstraße 7c",
               "postalCode":"99423",
               "addressLocality":"Weimar"
            }
         }
      }
   ],
   "startDate":"2017-06-01",
   "availableChannel":[
      {
         "type": ["ServiceChannel", "WebAPI" ],
         "serviceType":"OAI-PMH",
         "serviceUrl":"https://playground.oer-contentbuffet.info/oai"
      },
      {
         "type": ["ServiceChannel", "WebAPI" ],
         "serviceUrl":"https://playground.oer-contentbuffet.info/edu-sharing/rest",
         "documentation":"https://playground.oer-contentbuffet.info/edu-sharing/swagger/index.html"
      }
   ],
   "schemaVersion":"20190305",
   "dateModified":"2019-03-05",
   "license":[
     "https://creativecommons.org/licenses/by-sa/4.0/deed.de",
     "https://creativecommons.org/licenses/by/4.0/deed.de"
   ],
   "sameAs":[
      "https://jointly.info/",
      "https://twitter.com/OER_JOINTLY"
   ]
}
```

<script type="application/json" class="js-hypothesis-config">
  {
    "openSidebar": true
  }
</script>

<script async="" src="https://hypothes.is/embed.js"></script>
