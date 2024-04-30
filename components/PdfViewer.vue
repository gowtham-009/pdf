<!-- components/PdfViewer.vue -->
<template>
    <div>
      <iframe :src="pdfSrc" width="100%" height="600"></iframe>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      pdfSrc: {
        type: String,
        required: true
      }
    }
  };
  </script>
  