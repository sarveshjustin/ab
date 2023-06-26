# ab
```
module ab (a,b,c,d,f);
  input a,b,c,d;
  output f;
assign f = (~b&~d) | (c&d) | (~a&b&d) | (a&c);
endmodule

```
