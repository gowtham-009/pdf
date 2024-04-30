<!-- pages/MyPdfPage.vue -->
<template>
  <div>
    <h1 style="text-align: center;">pdf viewer</h1>
    <PdfViewer :pdfSrc="pdfUrl" />
  </div>
</template>

<script>
import PdfViewer from '~/components/PdfViewer.vue';

export default {
  components: {
    PdfViewer
  },
  data() {
    return {
      pdfUrl: '/gowtham.pdf'
    };
  }
};
</script>
