#sensor-gyroscope
See the [component page](http://fvitullo.github.io/sensor-gyroscope/components/sensor-gyroscope/) for more information.


#Installation
```
bower install sensor-gyroscope
```

#Use
```html
<sensor-gyroscope></sensor-gyroscope>
```
```javascript
<script>
  var gyroscope = document.querySelector('sensor-gyroscope');
  gyroscope.addEventListener('onGyroscopeUpdate', function(e) {
    console.log('alpha:' + this.alpha,
                'beta:' + this.beta,
                'gamma:' + this.gamma);
  });
</script>
```
