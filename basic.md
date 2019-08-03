# Layout Basic

```
plt.subplots(*args, **kwargs)
plt.figure(*args, **kwargs)

# [kw]args
plt.subplots(constrainted_layout=True)
plt.rcParams['figure.constrained_layout.use'] = True

fix, ax = plt.subplots

# 축(ax)에 그래프 그리기
ax.plot([1, 2])

# nbins: 눈금 표시 수
ax.locator_params(nbins=3)

# label: 축 캡션
ax.set_xlabel('x-label', fontsize=12)
ax.set_ylabel('y-label', fontsize=12)

# title: plot title
ax.set_title('Title', fontsize=16)
```

# Color object

```
Colormap
Normalize, LinearSegmentedColormap, ListedColormap
vmin, vmax, clip
```
