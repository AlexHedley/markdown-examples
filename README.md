# markdown-examples
Markdown Examples

## Mermaid

```mermaid
graph LR;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Blockquote Annotations

> **Note**: This is a note

> **Warning**: This is a warning

## Code Reference

https://github.com/AlexHedley/markdown-examples/blob/44cb0a717f6f4e18bda56b3f8f843370fdd6bb24/customer.sql#L1

## Diff

``` diff
diff --git a/filea.extension b/fileb.extension
index d28nd309d..b3nu834uj 111111
--- a/filea.extension
+++ b/fileb.extension
@@ -1,6 +1,6 @@
-oldLine
+newLine
```

```diff
public class Hello1
{
   public static void Main()
   {
-      System.Console.WriteLine("Hello, World!");
+      System.Console.WriteLine("Rock all night long!");
   }
}
```

## Math Support

- [Math support in Markdown](https://github.blog/2022-05-19-math-support-in-markdown/)

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

