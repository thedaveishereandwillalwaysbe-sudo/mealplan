# Back In Shape — Household Meal Plan

A self-contained, mobile-friendly meal planning tool for a household of 3 adults + 1 child (age 6), built around the Waitrose Essential range with integrated training nutrition targets.

**[View Live →](https://YOUR_USERNAME.github.io/meal-plan/)** *(update after enabling GitHub Pages)*

---

## What This Is

A single HTML file with five tabs:

| Tab | What It Does |
|---|---|
| 🛒 **Ingredients** | Full shopping list split into Weekly Fresh (~£120) and Stock Cupboard (fortnightly, ~£65). Verified Waitrose prices. Shelf life for every item. **Copy buttons** that format items for Waitrose Multi-Search — paste and go. |
| 🍽️ **Meals** | Two-week rotating meal plan (Week A / Week B) with day cards. Sunday batch cook → Monday prep → grab-and-go Tue–Thu → fresh cook Fri/Sat. Child meals (5:30pm) shown separately. |
| 📖 **Recipes** | 17 collapsible recipes with verified temperatures, timings, and macros. DREO ChefMaker and slow cooker methods integrated. Bialetti morning coffee routine. |
| 🔧 **Kit** | Equipment checklist with buy links. Containers, commute kit, cooking equipment (owned items marked). |
| 🛒 **Order Helper** | 48 clickable Waitrose search links with checkbox progress tracking. Backup for items not found via Multi-Search. |

## Key Features

- **Waitrose Multi-Search integration** — copy buttons format the shopping list for direct paste into Waitrose's Multi-Search tool
- **Two-shop system** — weekly fresh + fortnightly stock cupboard, with separate copy buttons for each
- **DREO ChefMaker recipes** — Chef Mode settings, probe temperatures, air fry times for every applicable recipe
- **Slow cooker Bolognese** — Sunday batch cook with 8 min active time
- **No mackerel** — replaced with hot smoked herring and tinned sardines (Waitrose mackerel suspension, April 2026)
- **No tuna** — smoked herring is the primary portable protein
- **Child meal planning** — 6-year-old's preferences (pasta, sausages, mac & cheese) with gentle diet expansion strategy
- **Mobile-friendly** — designed to be used in the kitchen from a phone

## Hosting on GitHub Pages

1. Create a new repository (e.g. `meal-plan`)
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your site will be live at `https://YOUR_USERNAME.github.io/meal-plan/`

## Version History

| Version | Changes |
|---|---|
| v1 | Initial 3-tab plan (ingredients, meals, kit) |
| v2 | +Recipes tab, egg preferences, lentil dhal, stock items, Sunday-first week |
| v3 | DREO ChefMaker integration, Bialetti coffee, slow cooker Bolognese |
| v4 | Mackerel → herring/sardines, split weekly/fortnightly shopping lists |
| v5 | Order Helper tab with 48 Waitrose search links + progress tracking |
| v6 | Multi-Search copy buttons for one-click Waitrose ordering |

## Built From

This meal plan supports the **Back In Shape V2.1 — ROC Trilogy** training programme (16-month periodised plan targeting the ROC Trilogy 2027: Wales, England, Scotland).

---

*Single-file, no dependencies, no build step. Just HTML + CSS + vanilla JS.*
