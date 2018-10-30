<template>
  <div>
    <nuxt/>
  </div>
</template>

<script>
const hm = {
  type: 'text/javascript',
  innerHTML: `
      var _hmt = _hmt || [];
      (function() {
        var hm = document.createElement('script');
        hm.src = 'https://hm.baidu.com/hm.js?49785f0478d709a92e396c4b7b706729';
        var s = document.getElementsByTagName('script')[0];
        s.parentNode.insertBefore(hm, s);
      })();`
}
const script = process.env.NODE_ENV === 'production' ? [hm] : []
export default {
  head: { script, __dangerouslyDisableSanitizers: ['script'] }
}
</script>
