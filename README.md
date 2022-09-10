# alphabet_logo
make each Latin character with LOGO and circles

https://www.calormen.com/jslogo/


## Draw a Circle
```logo

; circle
to circle
  repeat 360 [  
  fd 2
  right 1]
  wait :delay
end


```

## Define P letter
```logo
;define P letter
  to P
      I1
      repeat 290 [
      right 1
      fd 5
      circle
      ]
      ; ready for next letter
      pu
      seth 0
      bk 133
      right 90
      fd 450
      seth 0
      pd
  end
```

## Output


![image](https://user-images.githubusercontent.com/110537772/189468810-0bfc07b1-2db1-4ab7-bf29-adeb33372c04.png)



