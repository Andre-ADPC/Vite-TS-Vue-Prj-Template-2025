# The Original `package.json` File After Initial Project Config

{
"name": "thedesiredprojectname",
"version": "0.0.0",
"private": true,
"type": "module",
"scripts": {
"dev": "vite",
"build": "run-p type-check \"build-only {@}\" --",
"preview": "vite preview",
"test:unit": "vitest",
"build-only": "vite build",
"type-check": "vue-tsc --build --force",
"lint:oxlint": "oxlint . --fix -D correctness --ignore-path .gitignore",
"lint:eslint": "eslint . --ext .ts,.vue,.tsx --fix",
"lint": "run-s lint:eslint lint:oxlint",
"format": "prettier --write src/"
},
"dependencies": {
"pinia": "^2.2.6",
"tailwindcss-opentype": "^1.1.0",
"vue": "^3.5.12",
"vue-router": "^4.4.5"
},
"devDependencies": {
"@tsconfig/node22": "^22.0.0",
"@types/jsdom": "^21.1.7",
"@types/node": "^22.9.0",
"@typescript-eslint/eslint-plugin": "^8.17.0",
"@typescript-eslint/parser": "^8.17.0",
"@vitejs/plugin-vue": "^5.1.4",
"@vitejs/plugin-vue-jsx": "^4.0.1",
"@vitest/eslint-plugin": "1.1.7",
"@vue/eslint-config-prettier": "^10.1.0",
"@vue/eslint-config-typescript": "^14.1.3",
"@vue/test-utils": "^2.4.6",
"@vue/tsconfig": "^0.5.1",
"autoprefixer": "^10.4.20",
"critical": "^7.2.1",
"eslint": "^9.14.0",
"eslint-plugin-oxlint": "^0.11.0",
"eslint-plugin-vue": "^9.30.0",
"jsdom": "^25.0.1",
"npm-run-all2": "^7.0.1",
"oxlint": "^0.11.0",
"postcss": "^8.4.49",
"postcss-import": "^16.1.0",
"postcss-nested": "^7.0.2",
"prettier": "^3.3.3",
"stylelint": "^16.10.0",
"stylelint-config-standard": "^36.0.1",
"tailwindcss": "^3.4.15",
"typescript": "~5.6.3",
"vite": "^5.4.10",
"vite-plugin-vue-devtools": "^7.5.4",
"vitest": "^2.1.4",
"vue-tsc": "^2.1.10"
}
}

# The `package.json` File Before Adding Tests & React

{
"name": "thedesiredprojectname",
"version": "0.0.0",
"private": true,
"type": "module",
"scripts": {
"dev": "vite",
"build": "run-p type-check \"build-only {@}\" --",
"preview": "vite preview",
"test:unit": "vitest",
"build-only": "vite build",
"type-check": "vue-tsc --build --force",
"lint:oxlint": "oxlint . --fix -D correctness --ignore-path .gitignore",
"lint:eslint": "eslint . --ext .ts,.vue,.tsx --fix",
"lint": "run-s lint:eslint lint:oxlint",
"format": "prettier --write src/"
},
"dependencies": {
"pinia": "^2.2.6",
"tailwindcss-opentype": "^1.1.0",
"vue": "^3.5.12",
"vue-router": "^4.4.5"
},
"devDependencies": {
"@tsconfig/node22": "^22.0.0",
"@types/jsdom": "^21.1.7",
"@types/node": "^22.9.0",
"@typescript-eslint/eslint-plugin": "^8.17.0",
"@typescript-eslint/parser": "^8.17.0",
"@vitejs/plugin-vue": "^5.1.4",
"@vitejs/plugin-vue-jsx": "^4.0.1",
"@vitest/eslint-plugin": "1.1.7",
"@vue/eslint-config-prettier": "^10.1.0",
"@vue/eslint-config-typescript": "^14.1.3",
"@vue/test-utils": "^2.4.6",
"@vue/tsconfig": "^0.5.1",
"autoprefixer": "^10.4.20",
"critical": "^7.2.1",
"eslint": "^9.14.0",
"eslint-plugin-oxlint": "^0.11.0",
"eslint-plugin-vue": "^9.30.0",
"jsdom": "^25.0.1",
"npm-run-all2": "^7.0.1",
"oxlint": "^0.11.0",
"postcss": "^8.4.49",
"postcss-import": "^16.1.0",
"postcss-nested": "^7.0.2",
"prettier": "^3.3.3",
"stylelint": "^16.10.0",
"stylelint-config-standard": "^36.0.1",
"tailwindcss": "^3.4.15",
"typescript": "~5.6.3",
"vite": "^5.4.10",
"vite-plugin-vue-devtools": "^7.5.4",
"vitest": "^2.1.4",
"vue-tsc": "^2.1.10"
}
}

# The `package.json` File After Adding Tests & React