# ab
```
module zen (
  input x, y, z, w,
  output f
);

  assign f = (~y & z) | (x & y) | (y & w);

endmodule
```
