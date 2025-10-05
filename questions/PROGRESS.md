# Easy 

- [4] Pick Ok 
- [7] Readonly Ok
- [11] Tuple to Object Ok
- [14] First of Array => Ok => type First<T extends any[]> = T extends [infer K, ...any[]] ? K : never
- [18] Length of Tuple => Ok => type Length<T extends readonly any[]> = T["length"] 
- [43] Exclude => OK => type MyExclude<E, O> = E extends O ? never : E