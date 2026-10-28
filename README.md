body {
            /* 修改这里：将原先的纯色和光晕，替换为从上到下的线性渐变 */
            background: linear-gradient(to bottom, #0f172a, #1e293b, #0f172a);
            
            /* 如果你想要更丰富的色彩渐变，也可以换成类似下面这种：
               background: linear-gradient(to bottom, #1a1c29, #2e1065, #0f172a); */

            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: var(--text-color);
            padding: 20px;
        }

深邃星空蓝渐变（沉稳大气，默认推荐）background: linear-gradient(to bottom, #090d16, #1e293b, #090d16);

优雅暗夜紫渐变（科技感、偏赛博风）background: linear-gradient(to bottom, #0f0c1b, #2e1065, #0f0c1b);

高级灰黑渐变（极致极简）background: linear-gradient(to bottom, #18181b, #27272a, #18181b);
